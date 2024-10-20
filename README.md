# SteavenLinux
![Profile Image](https://avatars.githubusercontent.com/u/128651597?s=400&u=cfe5c1038e6b898b6a21b662723c8ee208225f8f&v=4)


##  Repos
run
```sh
sudo pacman-key --keyserver keyserver.ubuntu.com --recv-keys F3B607488DB35A47 3056513887B78AEB A367FB01AE54040E 7533BAFE69A25079 74F5DE85A506BF64 CB9574E032B61686007E808265F0CB198279AF38
sudo pacman-key --lsign-key F3B607488DB35A47 3056513887B78AEB A367FB01AE54040E 7533BAFE69A25079 74F5DE85A506BF64 CB9574E032B61686007E808265F0CB198279AF38
sudo pacman -U 'https://mirror.cachyos.org/repo/x86_64/cachyos/cachyos-keyring-20240331-1-any.pkg.tar.zst' \
'https://mirror.cachyos.org/repo/x86_64/cachyos/cachyos-mirrorlist-18-1-any.pkg.tar.zst' \
'https://mirror.cachyos.org/repo/x86_64/cachyos/cachyos-v3-mirrorlist-18-1-any.pkg.tar.zst' \
'https://mirror.cachyos.org/repo/x86_64/cachyos/cachyos-v4-mirrorlist-6-1-any.pkg.tar.zst' \
'https://mirror.cachyos.org/repo/x86_64/cachyos/pacman-7.0.0.r3.gf3211df-2-x86_64.pkg.tar.zst' \
'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-keyring.pkg.tar.zst' \
'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-mirrorlist.pkg.tar.zst' \
'https://ftp.belnet.be/mirror/endeavouros/repo/endeavouros/x86_64/endeavouros-keyring-20231222-1-any.pkg.tar.zst' \
'https://ftp.belnet.be/mirror/endeavouros/repo/endeavouros/x86_64/endeavouros-mirrorlist-24.9-1-any.pkg.tar.zst' \
'https://mirrors.dotsrc.org/blackarch/blackarch/os/x86_64/blackarch-keyring-20180925-5-any.pkg.tar.zst' \
'https://mirrors.dotsrc.org/blackarch/blackarch/os/x86_64/blackarch-mirrorlist-20240523-1-any.pkg.tar.zst' \
'https://github.com/arcolinux/arcolinux_repo/raw/refs/heads/main/x86_64/arcolinux-keyring-20251209-3-any.pkg.tar.zst' \
'https://github.com/arcolinux/arcolinux_repo/raw/refs/heads/main/x86_64/arcolinux-mirrorlist-git-24.03-12-any.pkg.tar.zst'
```

then replace your pacman.conf with this [pamcan.conf](https://github.com/SteavenLinux/SteavenLinux/raw/refs/heads/main/pacman.conf)

## SteavenLinux Core Packages
`sudo pacman -Syu SteavenLinux-printering-meta fastfetch gamescope-legacy-bin hyfetch steavenlinuxname steavensettings SteavenSettingsExtra SteavenLinux-plymouth-theme SteavenBuntu-Wallpapers`

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
