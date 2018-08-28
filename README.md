# Win-sudo (For Powershell)
Forked from the original Win-sudo, <b> originally created by jamestel </b> - this version will allow you to quickly switch into an elevated Powershell instance. (Oh and also run powershell scripts as Administrator)

"Emulated sudo command to elevate (Run As Administrator)" PowerShell and or applications via UAC."
 
## How To Use
Simply download and place `su.bat` into your `ToBeConfirmed` folder.

* Unlimited arguments are supported when lauching an elevated application or script.

#### Examples:
```
su test.ps1
```

```
su test.ps1 -t -w -192 etc
```

```
su test.ps1 -t -w -192 etc
```
```
su "C:\Users\Username\Test\test.ps1" -v
```
