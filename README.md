# SteavenLinux
![Profile Image](https://avatars.githubusercontent.com/u/128651597?s=400&u=cfe5c1038e6b898b6a21b662723c8ee208225f8f&v=4)


##  Repos
run
```sh
sudo pacman-key --recv-keys 5D47A0A4882E9619CCF7D0A57FD4F55D1E0AA9CA
sudo pacman-key --lsign-key 5D47A0A4882E9619CCF7D0A57FD4F55D1E0AA9CA
```

in pacman.conf add 
```sh
[SteavenRepo]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/steavenrepo-mirrorlist
```
before any repo

create `/etc/pacman.d/steavenrepo-mirrorlist` and add in it
```sh
Server = http://arabcraft.ddns.net:8080/x86_64
Server = http://arabcraft.omarhanykasban.online:8080/x86_64
Server = http://steavenrepo.omarhanykasban.online
Server = http://192.168.1.120:8080/x86_64
Server = file:///mnt/Omar-PC-Server/home/omarhanykasban/SteavenRepo/x86_64
```
## SteavenLinux Packages

Core Packages: `sudo pamcan -Syu steavenlinuxname SteavenLinux-plymouth-theme SteavenBuntu-Wallpapers`

Settings: `sudo pacman -Syu SteavenSettings`

Extra Settings: `sudo pacman -Syu SteavenSettings`

CachyOS Settings: `sudo pacman -Syu SteavenCachyosSettings`

Printers: `sudo pacman -Syu SteavenLinux-printering-meta`

Fastfetch and hyfetch: `sudo pacman -Syu fastfetch hyfetch`

Gamescope for old AMD gpus: `sudo pacman -Syu gamescope-legacy-bin`

## Gpu Drivers
Nvidia: `sudo pacman -Syu SteavenLinux-Nvidia-open-meta`

Nvidia but older: `sudo pacman -Syu SteavenLinux-Nvidia-proprietary-meta`

Amd: `sudo pacman -Syu SteavenLinux-Amd-meta`

Intel: `sudo pacman -Syu SteavenLinux-Intel-meta`

## De
Kde: `sudo pacman -Syu SteavenLinux-plasma-meta`

Gnome: `sudo pacman -Syu SteavenLinux-gnome-meta`

## Gaming
PC: `sudo pacman -Syu SteavenLinux-Gaming-meta`

Consoles: `sudo pacman -Syu SteavenLinux-Emulators-meta`

## Plymouth

### steavenlinux first in the video
`sudo plymouth-set-default-theme -R steavenlinux`

### steavenlinux2 secound in the video
`sudo plymouth-set-default-theme -R steavenlinux2`

<video width="640" height="360" controls="controls" src="https://github.com/SteavenLinux/SteavenLinux/raw/refs/heads/main/ah.mp4"></video>

