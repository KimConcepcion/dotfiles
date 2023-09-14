# dotfiles
This repo contains my preferred settings and configuration files for different tools I use for development work.

## Install Starship (With Bash)
For details check out: https://starship.rs

1. Download & install starship binary

`curl -sS https://starship.rs/install.sh | sh`

2. Add the starship init script at the end of your shell's config file

```
# ~/.bashrc

eval "$(starship init bash)"
```

3. Copy starship.toml from starship folder in this repo to the .config folder in your home directory
