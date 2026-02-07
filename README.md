# 🚀 Arch Linux Easy Setup Script

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

One-click setup script for Arch Linux that installs essential packages and configures the system for daily use. Combines the ease of Debian with the freshness of Arch.

## ✨ Features

- **Complete System Setup**: Installs 50+ essential packages
- **Media & Internet Ready**: Browsers, media players, recording tools
- **Arabic & International Support**: Fonts and language packs
- **AUR Integration**: Installs `yay` and popular AUR packages
- **Power Management**: Optional laptop optimizations
- **Security Focused**: Warns about potential risks, asks for confirmation
- **Clean & Maintainable**: Well-structured Bash script

## 📦 What's Included

### Core Packages:
- **Media**: MPV, VLC, OBS Studio
- **Browsers**: Firefox (with Arabic), Tor Browser
- **System**: NetworkManager, Flatpak, GParted, Btop
- **Tools**: Fastfetch, Filelight, Scrcpy, Kamoso
- **Fonts**: Noto fonts (with Arabic), DejaVu, Amiri
- **Compatibility**: Wine for Windows applications
- **Shell**: Fish shell (optional default)

### AUR Packages (Optional):
- Stacer (system optimizer)
- Visual Studio Code
- Spotube (Spotify client)
- ani-cli-arabic (anime CLI)
- Auto-cpufreq (power management)
- Input Remapper (keyboard customization)

## 🚀 Quick Start

### Method 1: Using `curl` (Recommended)
```bash
curl -L https://raw.githubusercontent.com/yourusername/archlinux-easy-setup/main/setup.sh -o arch-setup.sh
chmod +x arch-setup.sh
./arch-setup.sh
