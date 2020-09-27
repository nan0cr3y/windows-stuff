# windows-stuff

## Installing packages with Chocolatey
### Install Chocolatey on its own
open an Elevated (Admin) Powershell prompt  
```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))```
### Install Packages
bare essentials  
``` choco install firefox 7zip.install notepadplusplus.install putty.install winscp.install sumatrapdf.install -y```
basic stuff/QoL
```choco install powertoys wiztree f.lux sharex hwinfo everything spotify telegram.install rufus -y```
optional tools
```choco install vnc-viewer -y```
games
```choco install steam discord.install msiafterburner -y```
internet type ~~beat~~ stuff
```choco install openvpn qbittorrent -y```
misc packages
```
keepass
microsoft-windows-terminal
crystaldiskinfo
libreoffice-fresh
peazip.install
```

optional stuff
```
vscode.install
windirstat

```

media stuff
```
mkvtoolnix
handbrake
aimp
youtube-dl
ffmpeg
```

#### Laptop specifics
```
choco install intel-xtu intel-graphics-driver nvidia-display-driver
```
