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
