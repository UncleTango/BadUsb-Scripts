@echo off

rem Terminate Latest Program 
taskkill /f /fi "status eq running" /fi "IMAGENAME ne explorer.exe" /t /fi "CPUTIME ge 00:00:05" /fi "USERNAME eq %USERNAME%" /fi "SESSION eq %SESSIONNAME:~1%"

rem Terminate Latest Chrome Window
taskkill /f /fi "windowtitle eq Google Chrome" /fi "status eq running" /t /fi "CPUTIME ge 00:00:05" /fi "USERNAME eq %USERNAME%" /fi "SESSION eq %SESSIONNAME:~1%"
