# Powerlevel10k configuration

## Install Nord Fonts
```
sudo wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Meslo.zip -P /usr/share/fonts
sudo unzip -o /usr/share/fonts/Meslo.zip -d /usr/share/fonts
sudo rm -f /usr/share/fonts/Meslo.zip /usr/share/fonts/README* /usr/share/fonts/LICENSE*
sudo fc-cache -fv
```

## Usage
```
ln -s ~/.dotfiles/p10k/.p10k.zsh ~/.p10k.zsh
```
