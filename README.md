I mantain and update dotfiles and adapt to my needs (monitors,apps) and the hyprland and wayland version that I got.
* OS: Arch Linux x86_64
* Hyprland version:0.53.2
* Wayland version: wayland-scanner 1.24.0
* Terminal version (Ghostty): 1.2.3-2
* Sheel: zhs 5.9
# Original Links
* Original repository: https://github.com/luismendozamx/dotfiles
* Author: https://github.com/luismendozamx
Prueba
# Installation guide by Luis Mendoza
# Dotfiles

These are a collection of personal scripts and configs I have collected over the years, I use them to maintain a standard environment across my machines. Feel free to copy, clone, take inspiration, or do whatever you want with them.

Use at your own risk and make sure you know what you are doing.

## Requirements

This scripts assumes you have the following installed:

* zsh
* oh-my-zsh
* git
+* neovim using NvChad 

## Platform Support

This configs can be used on Linux and/or macOS. The linux configs also support Hyprland, but can be used on Gnome or KDE as well.

Linux with Hyprland

![Screenshot](./screenshot.png)

## Quick Setup

```bash
mkdir ~/dev/config
git clone https://github.com/luismendozamx/dotfiles.git ~/dev/config/dotfiles
cd ~/dev/config/dotfiles
./install.sh
```

## What's Included

- **Shell**: Zsh configuration with custom themes and aliases
- **Terminal**: Ghostty and Kitty configurations
- **Window Manager**: Hyprland setup with Waybar and Wofi (Linux)
- **Editor**: VSCode and Cursor settings
- **Utilities**: Custom scripts in `bin/`

## Structure

```
├── bin/           # Utility scripts
├── ghostty/       # Ghostty terminal config
├── git/           # Git configuration
├── hypr/          # Hyprland window manager (Linux)
├── kitty/         # Kitty terminal config
├── waybar/        # Status bar config (Linux)
├── wofi/          # App launcher (Linux)
└── zsh/           # Shell configuration
```

The installation script automatically detects your OS and installs appropriate configurations. Existing files are backed up to `~/.dotfiles_backup/`.
