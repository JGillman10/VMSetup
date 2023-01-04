# VMSetup
Setup for Linux environment

## Github CLI
https://docs.github.com/en/github-cli/github-cli/quickstart

## Build-essential
```bash
sudo apt install build-essential
```

## Misc Software for Neovim
If using WSL, these won't be installed
```bash
sudo apt install clang
sudo apt install g++
sudo apt install npm
```

## node and npm
these are needed for some treesitter components
use nvm package manager
https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
https://medium.com/@iam_vinojan/how-to-install-node-js-and-npm-using-node-version-manager-nvm-143165b16ce1

## Neovim Download
https://github.com/neovim/neovim/wiki/Installing-Neovim

## WSL Clipboard/Xclip with Neovim
for use in wsl: using the winyank, setup from the following link: https://github.com/neovim/neovim/wiki/FAQ#how-to-use-the-windows-clipboard-from-wsl
xclip works well in VM and dual boot systems

## Neovim setup
(in progress) https://github.com/JGillman10/nvim

## Alias in bashrc
```bash
alias python='python3'
alias vim='nvim'
```

**Need to make bash script to automate this stuff**
**Make one for WSL and one for VM/dual boot systems**
