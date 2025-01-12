# About running PowerShell scripts

This tool is written in PowerShell script. By default, Windows does not allow PowerShell scripts to be executed directly, so to execute them you must change the execution policy and grant permission beforehand.  
The shortcut included with this tool contains a specification that allows you to launch this tool by temporarily granting execution permission only while it is running.  
If for some reason you cannot launch the tool with this shortcut, either of the following measures are possible.

1. Recreate the Windows shortcut  
Right-click mollyvx_patch.ps1, and then create a shortcut for mollyvx_patch.ps1 in the same location  
Open the shortcut properties and set it as follows  
Target: `powershell.exe -ExecutionPolicy RemoteSigned -WindowStyle Hidden -File mollyvx_patch.ps1`  
Start in: blank(delete) *No problem if left as is  
Run: `Minimized`  
(After entering 'powershell.exe', it will automatically become the full path in your environment, such as C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe.)  

2. Manually run from the PowerShell console  
`Set-ExecutionPolicy RemoteSigned -Scope Process` (→ [Y] Yes)  
`.\mollyvx_patch.ps1`  
*If you use this method, the execution policy will be reverted when you close the PowerShell console.  
