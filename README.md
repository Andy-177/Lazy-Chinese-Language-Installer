# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

# Installation
## Linux/MacOS
- Make a backup of your current Neovim files:
```
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```
- Clone the starter
```
git clone https://github.com/Andy-177/Lazy-Chinese-Language-Installer.git ~/.config/nvim
```
- Remove the `.git` folder, so you can add it to your own repo later
```
rm -rf ~/.config/nvim/.git
```
- Start Neovim!
```
nvim
```
## Windows
- Make a backup of your current Neovim files:
```
# required
Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended
Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak
```
- Clone the starter
```
git clone [https://github.com/LazyVim/starter](https://github.com/Andy-177/Lazy-Chinese-Language-Installer.git) $env:LOCALAPPDATA\nvim
```
- Remove the .git folder, so you can add it to your own repo later
```
Remove-Item $env:LOCALAPPDATA\nvim\.git -Recurse -Force
```
- Start Neovim!
```
nvim
```
