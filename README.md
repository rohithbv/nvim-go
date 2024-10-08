# nvim-go

This repository holds the Neovim configuration for Go development.

## Installation

### Backup

if you have an existing neovim configuration, first back this up and clean out your neovim cache.

```
mv ~/.config/nvim ~/.config/nvim-backup
rm -rf ~/.local/share/nvim
```

### Install

To install this configuration on Linux & macOS, run the following command:

```
git clone git@github.com:rohithbv/nvim-go.git ~/.config/nvim
```

Then, open up neovim in order to download and install the base configuration packages.

## Modifying

### Custom Plugins

All custom plugins shown in videos should be added to the `lua/custom/plugins.lua` file.
