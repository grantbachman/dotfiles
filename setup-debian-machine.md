# Setting up a new Debian Jmachine

This file describes how I get some basic things set up on my Ubuntu machines.

## Keyboard

I use `localectl` to ensure proper keyboard config. It should already be installed on Debian machines. Running it once will set this map permanently.

```bash
localectl set-x11-keymap us pc105 '' caps:escape
```


## Terminal

I use [Alacritty](https://github.com/alacritty/alacritty). Install it from source, because otherwise you can't create a nice desktop icon for it. The instructions detail how to make the icon appear, so follow those.

### Configure

To configure alacritty, copy or symlink the alacritty.yml file in this repo to `$HOME/.config/alacritty/alacritty.yml`.

## Fonts

I use [Monaco Nerd Font](https://github.com/Karmenzind/monaco-nerd-fonts). Download the repository, copy the files to /usr/share/fonts/<custom-dir>/, reload `fc-cache`, and that should be it.
