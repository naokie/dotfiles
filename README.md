# naokie’s dotfiles

This repo is mostly for my new OSX.

## Homebrew

```zsh
# https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```zsh
brew bundle
```

## zsh

```zsh
echo /opt/homebrew/bin/zsh | sudo tee -a /etc/shells
chsh -s /opt/homebrew/bin/zsh
```
