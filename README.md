# cheats
Little pieces of code and stuff I'll need too infrequently to remember.

## Windows Tools
 * [Everything][1] - finds files
 * [Caffeine][2] - prevents display sleep
 * [Terminus][3] - usable terminal program
 * [Visual Studio Code][4] - a decent editor / IDE
 * [AquaSnap][5] - window tiling helper
 * [Rainmeter][6] - interactive desktop backgrounds
 
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

[1]: https://www.voidtools.com/
[2]: https://zhornsoftware.co.uk/caffeine/
[3]: https://eugeny.github.io/terminus/
[4]: https://code.visualstudio.com/
[5]: https://www.nurgo-software.com/products/aquasnap
[6]: https://www.rainmeter.net/
