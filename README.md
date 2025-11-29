<h3 align="center">
Fastfetch | Trapplus
</h3>

<h4 align="center">
Welcome to my fastfetch config presets repo.
</h4>

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a tool for fetching system information and displaying them in a pretty way. 
In this repo, I collect my config files that I designed for my [Arch Linux](https://archlinux.org/) [Hyprland](https://github.com/hyprwm/Hyprland) rice. 
Feel free to copy files and modify them or clone the complete repository.

<p align="center">
  <img src="./screenshots/tiling-mode.png" style="width: 100%;">
</p>

## Usage

Clone the repository into ``~/.local/share``

```sh
cd ~/.local/share
git clone https://github.com/LierB/fastfetch
```
and execute your preferred files (e.g. ``groups.jsonc`` or ``minimal.jsonc``) with 

```shell
fastfetch -c groups
fastfetch -c os
fastfetch -c arch
fastfetch -c full-info
```

```sh
fastfetch
# or with additional options e.g.
fastfetch --colors-block-range-start 9 --colors-block-width 3
```
