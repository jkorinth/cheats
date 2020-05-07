# cheats
Little pieces of code I'll need too infrequently to remember.

## PowerShell

Command | Description
------- | ------------------
`vim $profile`| Edit current profile config.
`Set-PSReadLineKeyHandler -Key Tab -Function Complete`| Sane tab-autocomplete.
`Set-PSReadLineOption -BellStyle None`| Friggin' bell. 
`Invoke-WebRequest -URI ... -OutFile ...` | `wget`/`curl`
`Get-ChildItem`| `ls`
`Select-String`| `grep` 
`Remove-Item -Force -Recurse`| `rm -rf`

## xkbmap

Toggle german/english keyboard layout with right shift, deactivate caps lock:

`setxkbmap -option grp:rshift_toggle,grp_led:scroll us,de -option caps:none`

Or: use `~/.Xkbmap` with just `-option grp:rshift_toggle,grp_led:scroll us,de -option caps:none`.
