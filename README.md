# dotfiles

### Example Images
![niri example](https://github.com/xNyxNox/dotfiles/tree/main/pictures/niri-monitor-1.png "Main Monitor in Niri")

![hyprland example](https://github.com/xNyxNox/dotfiles/tree/main/pictures/hyprland-monitors-both.png "Dual Monitors in Hyprland")

### Information
A remote backup of my dotfiles.  Things are always changing, so I don't recommend pulling changes without checking first.  I typically use these on Arch, although most are distro agnostic.

Usage typically involves just cloning the repository and pasting the desired folders into your .config directory.  Some require packages or configuration outside of .config which is not always included in this repo.

I will try to note any manual intervention required below:


1. zsh configuration relies on setting the zsh config directory in ~/.zprofile with 

    ```export ZDOTDIR="$XDG_CONFIG_HOME/zsh"```

2. You must set the btop theme yourself (likely to the theme in the btop/themes folder).  You can either use the TUI to change the theme or simply change the path in btop.conf

3. You must choose your own wallpaper in hyprpanel config and/or swww using `swww img wallpaperpath`.  I will provide my current wallpaper(s) as part of the repo, but you may need to set them yourself.  In addition, you will probably want to change your name and profile picture in hyprpanel to match your user.


List of packages I can remember (only install the ones you want):
**Universal**
btop
kitty
zsh
powerlevel10k
swaylock

**Niri**
niri
swaync
waybar
xwayland-satellite
swww

**Hyprland**
hyprland
hyprpanel

---

### Notes:

Before loading into a window manager, be sure to review the keybinds.  In Niri, you can open a list of important keybinds by pressing Super+Shift+/ or Super+?.  In both, pressing Super+Enter will bring you into a terminal where you can browse the config in your text editor of choice.

Waybar is vertical for use inside of Niri.  Hyprpanel is horizontal for use inside of hyprland.  Both *should* automatically launch when entering their respective session if installed.

Most of my zsh config that I don't think would be applicable to others (such as aliases and env variables) is kept in ~/.zprofile which is not included in this repo.  Please keep in mind that you may need to do some alteration to yours.

Any wallpapers included in the repo are not created by me.  Some of them have been altered slightly to better match my setup.

Much of the configuration are also things that I have grabbed from other places and modified to work for me.  I don't claim anything in this repository is 100% original work.
