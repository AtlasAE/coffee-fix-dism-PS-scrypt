basic dsim repair scrypt in the correct order 

to run open powershell 
use these commands

cd file path

.\fix-coffee.ps1

if it does not run it may be your ex pol!!

to fix that 
use one of these commands


Permanent Machine-Wide Change (Requires Administrator)


"Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope LocalMachine"

or

Permanent Change for Only Your User Account (No Admin Required)



"Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser -Force"




then again
run in PS

cd file path to folder fix-coffee.ps1

is located in example 

cd C:\Users\Owner\Desktop\repair

.\fix-coffee.ps1




after choosing yes or no at the end of the scrypd you may opt out of the any key by pressing up on the arrow keys

and you may run addititional commands such as  

sfc /scannow



