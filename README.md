# dotfiles

This directory contains the dotfiles for my system.

## Requirements

Ensure you have the following installed on your system

### Git

```
brew install git
```

### GNU Stow

```
brew install stow
```

## Setup

First, check out the dotfiles repository in your home directory

```
cd ~
git checkout <repo>
```

then move to your `dotfiles` directory and then run GNU stow to create symlinks

```
cd ~/dotfiles
stow .
```
