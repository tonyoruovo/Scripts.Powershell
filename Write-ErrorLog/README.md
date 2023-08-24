A powershell function That is an emty template for an error or warning log

### useage

Load the function into a profile and do:

```shell
Write-ErrorLog -hostname "Server1" -env "PROD" -logicalname "APP1" -errormsg "Error Message" -exception "HResult 0789343" -scriptname "Test.ps1" -failinglinenumber "25" -failingline "Get-Service" -pscommandpath "Command pathc." -positionmsg "Position message" -stacktrace "Stack trace" -Verbose
```

To use properly, comment out the last 4 lines of code.