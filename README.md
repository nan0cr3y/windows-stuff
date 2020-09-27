# windows-stuff

## Installing packages with Chocolatey
### Install Chocolatey on its own
- Elevated (Admin) Powershell  
```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))```
### Install Packages
- bare essentials  
``` choco install firefox 7zip.install notepadplusplus.install putty.install winscp.install sumatrapdf.install```

### basic stuff/QoL
```choco install powertoys wiztree flux sharex hwinfo everything spotify telegram.install rufus```

### optional tools
```choco install vnc-viewer```

### games
```choco install steam discord.install  msiafterburner```

### internet type ~~beat~~ stuff
```choco install openvpn qbittorrent```


### misc packages
```
keepass
microsoft-windows-terminal
crystaldiskinfo
libreoffice-fresh
peazip.install
```

### optional stuff
```
vscode.install
windirstat

```

### media stuff
```
mkvtoolnix
handbrake
aimp
youtube-dl
ffmpeg
```

### Laptop specifics
```
choco install intel-xtu intel-graphics-driver nvidia-display-driver
```
