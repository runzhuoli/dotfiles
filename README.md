# iTerm2 + Oh My Zsh + Tmux + Tig

## Brew

website: https://brew.sh/

install brew:

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

## iTerm2

    brew cask install iterm2

Get the iTerm color settings

- [Solarized Dark theme](https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Solarized%20Dark%20-%20Patched.itermcolors) (patched version to fix the bright black value)
- [Solarized Light theme](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Light.itermcolors)
- [More themes @ iterm2colorschemes](http://iterm2colorschemes.com/)

## Oh My Zsh

install oh-my-zsh through brew:

    sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

rename zshrc to .zshrc and place it into "~/"

### Powerlevel9k

If you prefer the Powerlevel9k look with added info such as exit codes and timestamps on the right, run:

    git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k

Then edit your `~/.zshrc` and set `ZSH_THEME="powerlevel9k/powerlevel9k"`.

Powerlevel9k offers a whole lot more, best is to [check out these user made configs yourself](https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config).

## Tmux

install tmux through brew:

    brew install tmux

rename tumx.conf to .tmux.conf and place it into "~/"

## Tig

install tig through brew:

    brew install tig

rename tigrc to .tigrc and place it into "~/" 

## Neovim

install neovim through brew:

    brew install neovim

copy files under nvim to "~/.config/nvim" 

install vim-plug:

    curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
        https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

open nvim and run:

    :PlugInstall

active YouCompleteMe plugin:

    brew install python && brew install CMake

    pip3 install neovim

    ~/.config/nvim/plugged/YouCompleteMe/install.py --racer-completer --tern-completer
