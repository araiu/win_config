# H1
-----

[Ninite URL](https://ninite.com/7zip-discord-firefox-pythonx3-qbittorrent-spotify-vlc-vscode-winrar/) for: 
* 7zip
* discord
* firefox
* pythonx3
* qbittorrent
* spotify
* vlc
* vscode
* winrar

_Not sure if this URL is static (Dec, 2022 works ✅ )_


# Choco install

## Prerequisite
Run `Get-ExecutionPolicy`. If it returns `Restricted`, then run `Set-ExecutionPolicy AllSigned` or `Set-ExecutionPolicy Bypass -Scope Process`.

## Install 
_Run in privileged shell_
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
 ## Install additional packages
 ```
 choco install hit
 ```
