## Open cmd in this directory as admin:

- type `powershell` and validate

- type `set-executionpolicy unrestricted` and validate

> remember to type `set-executionpolicy restricted` after operation !


## To get an appx package information

- type `get-appxpackage *asphalt* | out-file D:\asphalt.txt` and validate


## Use this command to backup an app and her dependencies

> use each package fullname with global windows apps directory.

`.\Appx-Backup.ps1 -WSAppPath "C:\Program Files\WindowsApps\Microsoft.ZuneVideo_10.17112.19011.0_x64__8wekyb3d8bbwe" -WSAppOutputPath "D:\" -WSTools "path/to/wstools"`
