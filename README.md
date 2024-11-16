# SteavenLinux
![Profile Image](https://avatars.githubusercontent.com/u/128651597?s=400&u=cfe5c1038e6b898b6a21b662723c8ee208225f8f&v=4)


##  Repos
run
```sh
sudo pacman-key --recv-keys 53A8F6EE177504E66BBBCA20C1F0637C80E7C321
sudo pacman-key --lsign-key 53A8F6EE177504E66BBBCA20C1F0637C80E7C321
```

in pacman.conf add 
```sh
[SteavenLinux]
Server = https://steavenlinux.github.io/SteavenRepo/x86_64
[SteavenLinux2]
Server = http://arabcraft.ddns.net:80/x86_64
#Server = http://192.168.1.117/x86_64
```
before any repo

## SteavenLinux Packages

Core Packages: `sudo pamcan -Syu steavenlinuxname SteavenLinux-plymouth-theme SteavenBuntu-Wallpapers`

Settings: `sudo pacman -Syu SteavenSettings`

Extra Settings: `sudo pacman -Syu SteavenSettings`

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
PC: `sudo pacman -Syu SteavenLinux-gaming-meta`

Consoles: `sudo pacman -Syu SteavenLinux-emulators-meta`

## Plymouth

### steavenlinux first in the video
`sudo plymouth-set-default-theme -R steavenlinux`

### steavenlinux2 secound in the video
`sudo plymouth-set-default-theme -R steavenlinux2`

[Plymouth](https://github.com/SteavenLinux/SteavenLinux/raw/refs/heads/main/ah.mp4)
