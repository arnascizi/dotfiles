## Dotfiles with GNU stow

This directory contains the dotfiles for some configurations

## Requirements

Ensure yyou have the following installed on your system

### Git
```
apt install git
```

### Stow
```
apt install stow
```

### Neovim
```
https://github.com/neovim/neovim/releases/
```

## Instalation

First, clone the repo into the $HOME directory using git
```
git clone https://github.com/arnascizi/dotfiles.git
cd dotfiles
```

Then use GNU stow to create symlinks

```
stow .
```

For more info
```
https://www.youtube.com/watch?v=y6XCebnB9gs
```
