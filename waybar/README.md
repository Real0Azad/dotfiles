# Waybar Configs

A simple and clean Waybar configuration for Hyprland.

## Requirements

Install the required packages:

```bash
sudo pacman -S --needed otf-comicshanns-nerd noto-fonts-emoji swaync waybar
```

### Package Overview

* **Waybar** – Status bar for Wayland compositors.
* **SwayNC** – Notification center and notification daemon.
* **otf-comicshanns-nerd** – Nerd Font used by the configuration.
* **noto-fonts-emoji** – Emoji support.

## Installation

Clone the repository:

```bash
git clone https://github.com/Real0Azad/dotfiles.git
```

Copy the configuration files:

```bash
mv ~/.config/waybar ~/.config/waybar.backup 2>/dev/null
mkdir -p ~/.config/waybar
cp -r dotfiles/waybar/* ~/.config/waybar/
```

Restart Waybar:

```bash
pkill waybar && waybar &
```

## Preview
<img width="1919" height="1079" alt="2026-06-12_09-54" src="https://github.com/user-attachments/assets/885f0b40-5e4f-46ec-9ee1-46139fd746ae" />

## Notes

This configuration was created and tested on Arch Linux with Wayland.

Feel free to modify it to fit your setup.
