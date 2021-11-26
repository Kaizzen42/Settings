# Basic Macbook setup
1. Enable three finger drag from SystemPreferences -> Accessibililty -> PointerControl -> Trackpad Options.
2. Enable one finger tap, and 2 finger tap for right click from SystemPreferences -> Mouse
3. Enable fast key repeats from the keyboard settings.
4. Get firefox.

# Settings
Vimrc, itermProfile etc.

## VIM Steps:
1. Install the pathogen package manager:
```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
2. Get the solarized color scheme by following instructions here:
    https://github.com/altercation/vim-colors-solarized
3. Copy the code from the vimrc into ~/.vimrc.

Don't source this, because its not meant to be executed as a bash script. Vim gets it.

## Setting up SSH for Git
1. Generating a new key
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
2. Adding it to the github repository
 https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

## Iterm2

1. Download Iterm2
2. Change theme to solarized following steps: https://michaelheap.com/solarized-with-iterm2/
