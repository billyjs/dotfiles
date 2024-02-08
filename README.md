# dotfiles

Symlink my dotfiles to the home directory using GNU stow.

## Usage

### Install or update

`./install.sh`

### Uninstall
    
`./uninstall.sh`

## List of dotfiles

* `.Brewfile` for packages and applications installed by brew - run `brew bundle -g` to install packages and applications
* `.Brewfile.personal` for personal packages and applications - run `brew bundle --file .Brewfile.personal` to install
* `.Brewfile.work` for work related packages and applications - run `brew bundle --file .Brewfile.work` to install

## TODO dotfiles

* `.zshrc`
* `.gitconfig`