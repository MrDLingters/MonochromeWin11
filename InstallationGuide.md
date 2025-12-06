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

Download this repo or clone it using:
```
git clone https://github.com/sundathree/.dotfiles
```
Move .config folder to your home ($Env:%USERPROFILE% or just %USERPROFILE%) folder and move the contents inside the powershell folder to your powershell folder, if you don't know where it is you can find it by typing ```$PROFILE``` inside your terminal.

### 🖼️ Komorebi:
You will need to set up a user variable in order for komorebi to work properly, open your start menu and search for View advanced system settings, once open, click on Environment Variables > User Variables > New, set the variable name to `KOMOREBI_CONFIG_HOME` and the value to `$Env:USERPROFILE/.config/komorebi`. If everything has been done correctly, running `komorebic check` on your powershell terminal should display `KOMOREBI_CONFIG_HOME detected: C:/Users/(username)/.config/komorebi`.

### 🍫 YASB:
This repo comes with the default YASB initial config. Inside the YASB folder there are folders for each theme, pick a flavor and move the contents from your selected theme's folder to .config/yasb. By default the location for the weather widget for my themes is set to Rio de Janeiro, you may want to change it to your current location, you can change it by looking for `weather > options > location` inside `config.yaml`.

## CLI Scripts:
Here are some CLI scripts I use with Git Bash and Powershell, either for fun or daily usage:
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch) - fetches system info<br/>
`scoop install fastfetch`
- [Yazi](https://github.com/sxyazi/yazi) - terminal file manager<br/>
`scoop install yazi`
- [ani-cli](https://github.com/pystardust/ani-cli) - watch anime on your terminal (git bash only)<br/>
`scoop install ani-cli`
- [unimatrix](https://github.com/will8211/unimatrix) - python-made cmatrix alternative<br/>
`pip install git+https://github.com/will8211/unimatrix.git windows-curses`
- [rs-matrix](https://github.com/TitaniumBrain/rs-matrix) - rust-made cmatrix alternative (supports terminal transparency)<br/>
- [btop4win](https://github.com/aristocratos/btop) - terminal resource monitor<br/>
`scoop install btop`
- [Win11 Toggle Rounded Corners](https://github.com/rich-ayr/win11-toggle-rounded-corners) - i wonder what this does...<br/>
- [pipes-rs](https://github.com/lhvy/pipes-rs) - funny pipes haha<br/>
`scoop install pipes-rs`
