## bira-colors-modded.zsh-theme

### bira.zsh-theme modded to Oh-my-zsh

### Just added and modded colors to easy visualization on local user_host.

### Old:
local user_host="%B%(!.%{$fg[red]%}.%{$fg[green]%})%n@%m%{$reset_color%} "

### New: 
local user_host="%B%(!.%{$fg[red]%}.%{$fg[green]%})%n%{$fg[white]%}@%{$fg[cyan]%}%m%{$reset_color%} "


## TO INSTALL ON oh-my-zsh

[code]bash -c "$(curl -fsSLN https://raw.githubusercontent.com/DaniSheng/bira-colors-modded.zsh-theme/master/install.sh)"[/code]


