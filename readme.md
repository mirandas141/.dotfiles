# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
sudo apt-get install git
```

### Stow

```
sudo apt-get install stow
```

### fzf

See the following page for current instructions.
https://github.com/junegunn/fzf?tab=readme-ov-file#installation

```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone https://github.com/mirandas141/.dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
