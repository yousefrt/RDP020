## RDP
**create an workflow file with this code in it**

[open code file](https://raw.githubusercontent.com/yousefrt/RDP020/main/main.yaml)
then connect to RDP 

then create `rdpALWAYS.bat` and add this data inside it 
_____
@echo off

:loop

ping ats-publications.com -n 1

timeout /t 5 >nul

goto loop
_____

then run it
