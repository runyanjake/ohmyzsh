# ohmyzsh
My ohmyzsh config.

## Prerequisites
1. Install zsh. It should come by default with MacOS, else get it thru homebrew.
```
sudo apt get install zsh
```
2. Set zsh as default shell
```
chsh -s /bin/zsh
```

## Installation
1. Install omz
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
2. Remove the generated zshrc and link the one in this repo as a replacement. Note the file in this repo isn't hidden.
```
rm ~/.zshrc
ln -sfn /path/to/zshrc ~/.zshrc
```
3. Source ~/.zshrc or restart the terminal.
```
source ~/.zshrc
```


