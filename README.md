## Description

This sets up my osx environment with a few commands using brew and babashka. My osx environment
includes the main applications I rely on as well as my personal repositories e.g. my dotfiles.
This works on a macbook pro with an intel or m1 chip.

## Prerequisites

- Install [brew](https://github.com/homebrew/brew).
- Install babashka 0.3.7+ with brew.

## Main tasks

Setup all the things: `brew bundle install && bb setup`

Update all repositories: `bb repo-update`

## License

See LICENSE.md
