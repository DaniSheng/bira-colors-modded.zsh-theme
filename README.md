## bira-colors-modded.zsh-theme

### bira.zsh-theme modded to Oh-my-zsh

### Just added and modded colors to easy visualization on local user_host.

### Old:
local user_host="%B%(!.%{$fg[red]%}.%{$fg[green]%})%n@%m%{$reset_color%} "

### New: 
local user_host="%B%(!.%{$fg[red]%}.%{$fg[green]%})%n%{$fg[white]%}@%{$fg[cyan]%}%m%{$reset_color%} "

![screenshot-preview](https://github.com/DaniSheng/bira-colors-modded.zsh-theme/blob/main/bira-colors-modded_screenshot.png)

## 1 - FIRST

* INSTALLING ZSH

https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH#ubuntu-debian--derivatives-windows-10-wsl--native-linux-kernel-with-windows-10-build-1903

Ubuntu, Debian & derivatives (WSL on Windows 10)

`sudo apt-get install zsh zsh-common zsh-doc`


## 2 - SECOND

* Oh My Zsh

Basic Installation

https://github.com/robbyrussell/oh-my-zsh#basic-installation

Oh My Zsh is installed by running one of the following commands in your terminal. You can install this via the command-line with either curl or wget.

* via curl

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

* via wget

`sh -c "$(wget -O- https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

* Change your default shell

`sudo chsh -s $(which zsh)`

## 3 - THIRD

## TO INSTALL Bira Colors Modded ZSH-TEME ON _Oh-My-Zsh_

On ZSH with on-my-zsh:

_*Via curl*_

_Copy, Paste and press Enter... this:_

`bash -c "$(curl -fsSLN https://raw.githubusercontent.com/DaniSheng/bira-colors-modded.zsh-theme/master/install.sh)"`
