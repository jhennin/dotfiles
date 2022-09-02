# dotfiles
This repository is used to consolidate local development environment configurations (e.g. Vim, Git) in one place. It was adopted from [Raphael Brugier dotfiles repo](https://github.com/raphaelbrugier/dotfiles).


## Initial setup

1. Install homebrew:
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    brew update
    ```

2. `brew bundle install --file=mac/brewfiles/BrewfileDevenv` or `brew bundle install --file=mac/brewfiles/work/Brewfile`


## Zsh && Zgenom && install

    brew install zsh
    chsh -s /bin/zsh
    git clone https://github.com/jandamm/zgenom.git "${HOME}/.zgenom"
    cd ~/dotfiles
    ~/dotfiles/install.sh
    p10k configure
    ./osx-install-defaults.sh

## Vim

    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    vim +PluginInstall +qall



## Tools Requiring Manual Installation

1. [Pathogen|https://github.com/tpope/vim-pathogen] - Used to form VIM

