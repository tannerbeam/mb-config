# mb-config
Useful stuff for setting up a new OSX machine

## Useful Info 
- [Mac setup checklist from Sourab Bajaj](https://sourabhbajaj.com/mac-setup/)
- [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
- [Definitive guide to conda environments](https://towardsdatascience.com/a-guide-to-conda-environments-bc6180fc533)
- [Toggle dark mode keyboard shortcut](https://lifehacker.com/switch-between-dark-and-light-mode-on-your-mac-with-thi-1838488087)
- [Using .condarc conda config file](https://docs.conda.io/projects/conda/en/latest/user-guide/configuration/use-condarc.html#creating-and-editing)
- [GitHub markdown guide](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
- [How to sync Sublime packages across machines](https://packagecontrol.io/docs/syncing)

## Executable Files

- **defaults-write.sh** customize osx with write defaults and such 

## Config Files
Maintained in a different repo
[Clone from GitHub](https://git.autodesk.com/beamt/dotfiles)

## Install checklist

#### iTerm2
- `brew cask install iterm2` 
- [iterm2 color schemes](https://iterm2colorschemes.com/)

#### Homebrew Casks: 
- `brew update` --> Fetch latest version of homebrew and formula.
- `brew tap homebrew/cask` --> Tap the Caskroom/Cask repository from Github using HTTPS.
- `brew search [cask]` --> Searches all known Casks for a partial or exact match.
- `brew cask info [cask]` --> Displays information about the given Cask
- `brew cask install [cask]` --> Install the given cask.
- `brew cleanup` --> Remove any older versions from the cellar       

#### ZShell (zsh) 
- `brew install zsh` 
- `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`  
- `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

#### Source Code Pro Font
- `brew tap homebrew/cask-fonts`
- `brew cask install font-source-code-pro`

#### Sublime Text 
- `brew cask install sublime-text`
automatically adds a symlink for `subl [filename]` 

installed packages listed in `Package Control.sublime-settings`

packages to install: 
- package control
- conda
- markdown extended
- monokai extended
- pretty JSON

#### Git 
- `brew install git` 

#### Conda
Dependencies installed automtically with consent. JDK required prior to installing R. Add environment specifications to `environment.yml` files in GitHub repos.

- `brew cask install miniconda`


