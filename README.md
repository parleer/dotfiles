# parleer dotfiles

## dotfiles

My personal dotfiles. 


This is a work in progress. I'll eventually have an installation script that
actually works, but for now the text below is just placeholder. 


Inspiration from https://github.com/holman/dotfiles

## install


Run this:

```sh
git clone http://github.com/parleer/dotiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.

The main file you'll want to change right off the bat is `zsh/zshrc.symlink`,
which sets up a few paths that'll be different on your particular machine.

`dot` is a simple script that installs some dependencies, sets sane OS X
defaults, and so on. Tweak this script, and occasionally run `dot` from
time to time to keep your environment fresh and up-to-date. You can find
this script in `bin/`.


