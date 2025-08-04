# dotfiles

This directory contains the dotfiles for my system.

## Requirements

Ensure you have the following installed on your system

### Git

```
brew install git
```

### GNU Stow

```
brew install stow
```

## Setup

First, check out the dotfiles repository in your home directory

```
cd ~
git checkout https://github.com/axxander/dotfiles
```

then move to your `dotfiles` directory and then run GNU stow to create symlinks

```
cd ~/dotfiles
stow */
```

Within `~/dotfiles`, we have a directory for each configuration. When within any given directory, you ust write your configurations as if you were in the home directory. `stow */` is equivalent to running `stow <pkg_name>` for all stow packages.
