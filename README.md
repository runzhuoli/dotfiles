# iTerm2 + Oh My Zsh + Tmux + Tig

## Brew

website: https://brew.sh/

install brew:

    brew cask install iterm2

## iTerm2

    brew cask install iterm2

Get the iTerm color settings

- [Solarized Dark theme](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors) (patched version to fix the bright black value)
- [Solarized Light theme](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Light.itermcolors)
- [More themes @ iterm2colorschemes](http://iterm2colorschemes.com/)

## Oh My Zsh

    sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

### Powerlevel9k

If you prefer the Powerlevel9k look with added info such as exit codes and timestamps on the right, run:

    git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k

Then edit your `~/.zshrc` and set `ZSH_THEME="powerlevel9k/powerlevel9k"`.

Powerlevel9k offers a whole lot more, best is to [check out these user made configs yourself](https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config).

## Tmux

    brew install tmux

## Tig

    brew install tig
