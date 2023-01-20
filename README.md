# Linux Development Environment Setup
For developing software, using Linux is my preferred environment. I like to use Ubuntu, using WSL, a virtual machine, or dual boot all work great. VM and dual boot seem to work a little better, especially when connecting to microcontrollers and other peripherals. Below is my setup for development, I decided to document because I tend to forget something when setting up a fresh machine.

---

## Zshell
Using Zshell has autocomplete and integrated tools like Git. I use the default theme. <br>
https://github.com/ohmyzsh/ohmyzsh

## Github CLI
The Github CLI allows authentication over HTTPS and your password is stored. <br>
https://docs.github.com/en/github-cli/github-cli/quickstart <br>

Additional Git setup: <br>
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

---

## Neovim setup

## Build-essential
```bash
sudo apt-get install build-essential
```

## Misc Software for Neovim
If using WSL, these won't be installed.
```bash
sudo apt-get install clang
sudo apt-get install g++
sudo apt-get install npm
```

## node and npm
These are needed for some Treesitter components.
Use nvm package manager. <br>
https://docs.npmjs.com/downloading-and-installing-node-js-and-npm <br>
https://medium.com/@iam_vinojan/how-to-install-node-js-and-npm-using-node-version-manager-nvm-143165b16ce1

## Neovim Download
https://github.com/neovim/neovim/wiki/Installing-Neovim

## WSL Clipboard/Xclip with Neovim
For use in WSL, use winyank. <br>
https://github.com/neovim/neovim/wiki/FAQ#how-to-use-the-windows-clipboard-from-wsl <br> <br>
Xclip works well in VM and dual boot systems, can use Ubuntu package. <br>
```bash
sudo apt-get install xclip
```

## Neovim config
My personal Neovim config. <br>
https://github.com/JGillman10/nvim

## Alias in bashrc
Useful alias settings that I use.
```bash
alias python='python3'
alias vim='nvim'
```

---
### Future changes
It could be useful to create a bash script to automate these steps.
