# dotfiles

A small collection of shell and editor configuration files I keep in one
place so I can move between machines without re-doing everything by hand.

## Layout

- `bashrc-additions` - aliases and tweaks to source from ~/.bashrc
- `gitconfig.example` - personal git aliases and defaults
- `vimrc.example` - minimal vim settings that make sense for me

## Usage

Each file is meant to be symlinked or sourced, not copied wholesale:

```sh
ln -s ~/dotfiles/bashrc-additions ~/.bashrc-additions
echo 'source ~/.bashrc-additions' >> ~/.bashrc
```

The example files deliberately contain nothing machine-specific so they work
everywhere. Adjust the values to your own setup after linking.
