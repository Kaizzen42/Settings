# Basic Macbook setup
1. Enable three finger drag from SystemPreferences -> Accessibililty -> PointerControl -> Trackpad Options.
2. Enable one finger tap, and 2 finger tap for right click from SystemPreferences -> Mouse
3. Enable fast key repeats from the keyboard settings.
4. Get firefox.
5. Get Paste.

# Settings
Vimrc, itermProfile etc.

## Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/karanmatnani/.profile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

## Iterm2
1. Download Iterm2 https://iterm2.com/downloads.html
2. Change theme to solarized after the VIM settings, following steps: https://michaelheap.com/solarized-with-iterm2/


## VIM Steps:
1. Install the pathogen package manager:
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
2. Get the solarized color scheme by following instructions here:
    https://github.com/altercation/vim-colors-solarized
3. Copy the code from the vimrc into ~/.vimrc.

```
set ruler
set cursorline
set number
execute pathogen#infect()
syntax on
filetype plugin indent on
"" Solarized stuff
syntax enable
let g:solarized_termcolors=256
set background=dark
colorscheme solarized
set ts=4 sw=4
```

Don't source this, because its not meant to be executed as a bash script. Vim gets it.

## Setting up SSH for Git
1. Generating a new key
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
2. Adding it to the github repository
 https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account


## Optionally, install zsh and power10K theme
Refer https://gist.github.com/tzutalin/0afaad9a176960b2a27f35b7a264447a

https://github.com/romkatv/powerlevel10k#oh-my-zsh

Custom plugins
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zsh-users/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions

```

