# Version 0.0.1 Beta
## Base image: Ubuntu 22.04
## Desktop: GNOME

<br>


<a href="https://gofile.io/d/662A84"><img src="https://raw.githubusercontent.com/msm-linux/MSM-Linux-Release-Official/main/assets/download.png" alt="Download Button" /></a>


<br>

---
## Added:
    - Repository: multiverse
    - Repository: restricted
    - Repository: universe
    - i386 arch dpkg Added
    - flatpak
    - gnome-software-plugin-flatpak
    - gnome-software
    - firefox(ppa)
    - apt pkgs:
        - curl
        - git
        - python3
        - python3-pip
        - software-properties-common
        - ttf-mscorefonts-installer
        - ca-certificates
        - gnome-disk-utility
        - mpv
        - htop
        - neofetch
        - openssh-server
        - synaptic
        - ubuntu-restricted-extras
        - dconf-editor
        - pavucontrol
        - blueman
        - gnome-sushi
        - ffmpeg
        - ffmpegthumbnailer
        - cpupower-gui
        - net-tools
        - gthumb
        - gnome-firmware
        - python3-yaml
        - python3-dateutil
        - python3-pyqt5
        - python3-packaging
        - python3-requests
        - mainline (kernel manager)
    - flatpak (flathub pkgs)
        - com.github.muriloventuroso.pdftricks
        - com.github.tchx84.Flatseal
        - com.github.donadigo.appeditor
        - com.mattjakeman.ExtensionManager
        - org.gnome.clocks
        - de.haeckerfelix.Fragments
        - org.x.Warpinator
        - org.gnome.SoundRecorder
        - com.github.muriloventuroso.easyssh
    - gnome-tweaks
    - gnome-shell-extensions:
        - Sound Input & Output Device Chooser
        - User Themes
        - Caffeine
    - grub-customizer(+ppa)
    - folder-color (+ppa)
    - yaru-colors-folder-color (+ppa)
    - nautilus-admin
    - Font:
        - DroidSansMono (nerd-fonts)
        - Rubik
    - fish-shell (+ppa)
    - VS Code (proprietary)
## Removed:
    - firefox(snap)
    - snap-store(ubuntu-software)
    - gnome-3-38-2004
    - gtk-common-themes(snap)
    - snapd-desktop-integration
    - bare(snap)
    - core20(snap)
    - snapd
    - Eye of Gnome
    - Totem
    - Thunderbird
## Modified:
    - /etc/apt/preferences.d/nosnap.pref
    - /etc/apt/apt.conf.d/51unattended-upgrades-firefox
    - /etc/apt/preferences.d/mozillateamppa
    - ~/.config/fish
## Planned/Ideas to be implemented/removed:
    - Wine setup script
    - bottles
    - winetricks
    - deb-get
    - gnome media softwares(video+audio)[remove]
    - Rubik font
    - VS code (preferably codium)
    - Nala apt frontend
    - Switch to Calamares installer instead of Ubiquity
    - MSM linux configurator (WIP)

## MD5 Checksum
```
    27cdc27fdb67fcffeeea8641a2df0936  msm-linux-beta-v1.iso
```