# Mint + i3 Personal Configuration

A lightweight i3 setup on Linux Mint, tuned for simplicity and productivity.

## Prerequisites
- Linux Mint (any recent release)  
- i3 window manager (v4)  
- i3status (or compatible status bar)  
- dex, nm-applet, xss-lock, i3lock  
- pactl (PulseAudio)  
- rofi  

## Installation
```bash
# Backup existing i3 config
mv ~/.config/i3 ~/.config/i3.backup

# Clone this repo into your i3 folder
git clone https://github.com/<username>/mint-i3-config.git ~/.config/i3

# Reload i3 (Mod1+Shift+R)
