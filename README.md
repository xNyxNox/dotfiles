# dotfiles
A remote backup of my dotfiles.

Usage typically involves just cloning the repository and pasting the desired folders into your .config directory.  Some require packages or configuration outside of .config which is not always included in this repo.

I will try to note any manual intervention required below:

1. zsh configuration relies on setting the zsh config directory in ~/.zprofile with 

    ```export ZDOTDIR="$XDG_CONFIG_HOME/zsh"```

2. You must set the btop theme yourself.  You can either use the TUI to change the theme or simply change the path in btop.conf


