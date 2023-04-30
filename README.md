# Powershell
Windows Powershell upgrade or install
Search for the latest version of PowerShell:
Windows + R --> Powershell
check version
The following commands can be used to install PowerShell using the published winget packages:

Search for the latest version of PowerShell

From PowerShell

winget search Microsoft.PowerShell

Output:


Name               Id                           Version Source
--------------------------------------------------------------
PowerShell         Microsoft.PowerShell         7.3.4.0 winget
PowerShell Preview Microsoft.PowerShell.Preview 7.4.1.0 winget
Install PowerShell or PowerShell Preview using the id parameter


From Powershell:
winget install --id Microsoft.Powershell --source winget
winget install --id Microsoft.Powershell.Preview --source winget
