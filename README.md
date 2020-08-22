<div align="center">
<h1>fet.sh</h1>
fetch written in POSIX shell with no external commands
<br>
<img src="screenshot.png" width="250px">
</div>

### Installing
**Arch:** [fet.sh-git](https://aur.archlinux.org/packages/fet.sh-git/) (AUR)  
**Gentoo:** [app-misc/fetsh](https://gpo.zugaina.org/Overlays/guru/app-misc/fetsh) (GURU overlay)  
**Other Distros:** copy `fet.sh` to somewhere in $PATH

### Arguments
`fet.sh` accepts command line args, to see them, run,
```
$ ./fet.sh help
```

### Customization
`fet.sh` can be configured using environment variables, for example:
```
$ info='n os wm sh n' fet.sh
```
Supported options are:
- `accent` (0-7)
- `info`
- `separator`
