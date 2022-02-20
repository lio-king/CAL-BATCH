# CAL-BATCH
learning batch-script and here is the calculator program......
@echo off
:start
set /p Math=First number?
set /a Result=%Math%
echo %Result%
pause
cls
goto start
