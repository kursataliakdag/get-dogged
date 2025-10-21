# get-dogged

![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A harmless, Bash-based script that displays fake errors. (and maybe has some refrences in)

**NOTE**: Before downloading the ZIP file, please verify the SHA256.


## Features
- **Non-destructive**: Only shows fake errors. No real system changes are made to your computer.
- **Customizable**: Change the script to your liking (Error messages and music).
- **ZIP download**: Pre-packaged releases with ease of use.
- **Lightweight**: Uses zenity (GUI) and mpv or vlc. (video)

## Installation Process
1. Download the latest release (or any version):
```bash
https://github.com/kursataliakdag/get-dogged/releases
```
2. Unzip the archive
```bash
dogged to dogged-2, extract the mandatory files onto desktop. dogged-3 to mysteryman, files must be in the extracted folder. dogged-3.1 and later will require to have the mandatory files in the files folder in the extracted folder.
First use "chmod +x dogged.sh" to make the script executable, then "./dogged.sh" to run it. (Unquoted)
```

## Dependencies
- `zenity`for the dialog
- `mpv` OR `vlc` (recommended).
- Preferred Linux distro installation for the dependencies:
### VideoLAN VLC
```bash
sudo apt install vlc (Debian/Ubuntu)
sudo dnf install vlc (Fedora/RHEL)
sudo pacman -S vlc (Arch Linux)
sudo zypper install vlc (openSUSE)
sudo eopkg install vlc (Solus)
```
### zenity GUI
```bash
sudo apt install zenity (Debian/Ubuntu)
sudo dnf install zenity (Fedora/RHEL)
sudo pacman -S zenity (Arch Linux)
sudo zypper install zenity (openSUSE)
sudo eopkg install zenity (Solus)
```
## Okay, enjoy this thing I made!
