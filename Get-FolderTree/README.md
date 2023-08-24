A powershell function for printing a directory tree as a tree similar to the `tree` cmdlet but with file exclusion and inclusion features

### useage

Load the function into a profile and do:

```shell
Get-FolderTree -Path C:\myfolder -Exclude "node_modules","client",".git" -IncludeFiles -Force > C:\anyfolder\tree.txt
```

To use properly, comment out the last 4 lines of code.
