# .files

These are my dotfiles (for mac). Take anything you want, but at your own risk.

## Overview

## Install

On a fresh mac run to following first to setup xcode commandline tools

```bash
sudo softwareupdate -i -a
xcode-select --install
```

Continue starting the dotfiles installation

```bash
git clone https://github.com/svrooij/dotfiles-mac.git ~/.dotfiles
cd ~/.dotfiles
make
```

Or remote install

```bash
bash -c "`curl -fsSL https://raw.githubusercontent.com/webpro/dotfiles/master/remote-install.sh`"
```

## Inspiration

This repo is heavaly inspired by [webpro's repo](https://github.com/webpro/dotfiles).
