# Kitty Configs

A visually polished configuration for the [Kitty](https://github.com/kovidgoyal/kitty) terminal emulator, designed for daily use with a clean dark theme and transparency

## 📸 Preview

<img width="1919" height="1079" alt="screenshot" src="https://github.com/user-attachments/assets/885f0b40-5e4f-46ec-9ee1-46139fd746ae" />

## Requirements

Install the required packages:

```bash
sudo pacman -S --needed otf-comicshanns-nerd kitty
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Real0Azad/dotfiles.git
```

Copy the configuration files:

```bash
mv ~/.config/kitty/ ~/.config/kitty.backup 2>/dev/null
mkdir -p ~/.config/kitty
cp -r dotfiles/kitty/* ~/.config/kitty/
```

Notes
This configuration was created and tested on Arch Linux with Wayland.

Feel free to modify it to fit your setup.
