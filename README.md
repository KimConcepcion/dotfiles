# dotfiles
This repo contains my preferred settings and configuration files for different tools I use for daily development work.

## Linux
The linux folder contains some of the scripts I use daily, when working in a Linux environment.

### Install APT packages
I have gathered the typical APT packages I use in a __packages.txt__ file.
You can use the __xargs__ cmd to read the packages.txt file and input it to the __apt__ cmd
```
$ xargs sudo apt-get -y install < packages.txt
```

## Nerd fonts
Download Nerd fonts from: https://www.nerdfonts.com/

Personally, I use the following fonts:
* JetBrainsMono
* FiraMono

## Starship (With Bash)
For details check out: https://starship.rs

1. Download & install starship binary

`curl -sS https://starship.rs/install.sh | sh`

2. Add the starship init script at the end of your shell's config file

```
# ~/.bashrc

eval "$(starship init bash)"
```

3. Copy starship.toml from starship folder in this repo to the .config folder in your home directory
