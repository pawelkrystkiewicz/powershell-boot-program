# Powershell script for starting app on Windows

  To avoid spaces problem in path name first checkout directory in quotes: `cd "C:\Program Files\..."` then run just the execuable: `start target.exe`.

  Also run cmd without messages adding `@echo off`.

```
@echo off
cd "C:\Program Files (x86)\RealTemp3.70"
start RealTempGT.exe
exit

```
## Starting on boot
Add `.bat` file to directory that opens after running command `shell:startup`.
