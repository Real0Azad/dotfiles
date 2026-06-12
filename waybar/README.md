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
cp -r waybar/* ~/.config/waybar/
```

Restart Waybar:

```bash
pkill waybar && waybar &
```

## Preview

## Notes

This configuration was created and tested on Arch Linux with Wayland.

Feel free to modify it to fit your setup.
