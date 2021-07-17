# Setting up a new Ubuntu machine

This file describes how I get some basic things set up on my Ubuntu machines.

## Keyboard

I remap the Caps Lock key to Esc. I do this by using `gnome-tweak-tool`. Install with `sudo apt install gnome-tweak-tool`, then run it with `gnome-tweaks`. It'll open a GUI and there's an option for specifying Caps Lock behavior.

## Terminal

I use [Alacritty](https://github.com/alacritty/alacritty). Install it from source, because otherwise you can't create a nice desktop icon for it. The instructions detail how to make the icon appear, so follow those.

### Configure

To configure alacritty, copy or symlink the alacritty.yml file in this repo to `$HOME/.config/alacritty/alacritty.yml`.

## Fonts

I use [Monaco Nerd Font](https://github.com/Karmenzind/monaco-nerd-fonts).
