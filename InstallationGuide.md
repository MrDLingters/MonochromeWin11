# Installation Guide

## Fonts used:
All fonts are available on [nerdfonts.com](https://www.nerdfonts.com).

> [!WARNING]
> YASB will not work properly if the required fonts aren't installed, so make sure to install all fonts.

- JetBrainsMono Nerd Font
- FiraCode Nerd Font
- FiraMono Nerd Font
- Iosevka Nerd Font
- UbuntuSansMono Nerd Font
- Hack Nerd Font

## Programs:
First of all, make sure you have scoop installed, if you don't, follow the instructions over at scoop's [official website](https://scoop.sh/#/). After scoop is installed, you're going to need:

> Run all commands on your terminal, preferably using Powershell

- [Buckets](https://scoop.sh/#/buckets)<br/>
`scoop bucket add main`<br/>
`scoop bucket add extras`<br/>
`scoop bucket add NSPC911_le-bucket`<br/>
- [Komorebi](https://github.com/LGUG2Z/komorebi)<br/>
`scoop install komorebi`
- [YASB](https://github.com/amnweb/yasb)<br/>
`scoop install yasb`
- [CAVA](https://github.com/karlstav/cava)<br/>
`scoop install cava`

## Installation:

### 🍫 YASB:
This repo comes with the default YASB initial config. Inside the YASB folder there are folders for each theme, pick a flavor and move the contents from your selected theme's folder to .config/yasb. By default the location for the weather widget for my themes is set to Rio de Janeiro, you may want to change it to your current location, you can change it by looking for `weather > options > location` inside `config.yaml`.

## CLI Scripts:
Here are some CLI scripts I use with Git Bash and Powershell, either for fun or daily usage:
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch) - fetches system info<br/>
`scoop install fastfetch`
- [Yazi](https://github.com/sxyazi/yazi) - terminal file manager<br/>
`scoop install yazi`
