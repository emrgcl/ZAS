# ZAS
Source code for Project ZAS

# Project Information 
This project is used for automating contoso middleware operations with PowersHell

- Install requirements
- add documentation

## steps to reproduce

1. copy files
1. run msiexec
1. cleanup
1. Inform **Zeynel**


# Samples

Following code will cleanup files
```PowerShell
$Cred = Get-Credential
Invoke-Command -ComputerName 'Server1' -Credential $Cred
```