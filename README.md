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

Set zsh from Homebrew as default shell.

```zsh

```zsh
echo /opt/homebrew/bin/zsh | sudo tee -a /etc/shells
chsh -s /opt/homebrew/bin/zsh
```

Install zimfw.

```zsh
curl -fsSL https://raw.githubusercontent.com/zimfw/install/master/install.zsh | zsh
```
