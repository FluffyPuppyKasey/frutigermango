# Frutiger Aero themed MangoWC dotfiles

Fedora install:
```bash
sudo dnf update
sudo dnf install --nogpgcheck --repofrompath 'terra,https://repos.fyralabs.com/terra$releasever' terra-release
sudo dnf copr enable erikreider/swayosd
sudo dnf install rofi alacritty swww swaybg waybar mako grim wl-clipboard cava wlogout fontawesome-fonts-all mangowc swayosd nmtui
```

In order to get your monitor(s) set up you'll need to follow the MangoWC monitor rules.

Download this repo as a ZIP, extract all directories to `$HOME/.config`. Colour scheme file goes in `$HOME/.local/share/color-schemes`
