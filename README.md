# 42-dev-env-setup

This is a convenience script to automate the configuration and instalation of a simple development environment in 42 Barcelona's iMacs.

## What it does

- Installs and updates homebrew on the `$HOME/.brew` folder.
- Installs chezmoi, neovim, kitty, starship and obsidian downloading and extracting their binaries directly to either `/sgoinfre/Perso/$USER/.local/bin` or `$HOME/.local/bin`.
- Installs fzf via brew.
- Clones and installs my dotfiles via chezmoi.
