# Personal vim development environment
This is my personal development envirment configuration, a light weight vim configuration.
If you like it, feel free to fork it to your own repo and change as you want.

## Plugin list:
```
Plugin 'VundleVim/Vundle.vim'
Plugin 'scrooloose/nerdtree'
Plugin 'scrooloose/nerdcommenter'
Plugin 'tpope/vim-fugitive'
Plugin 'Xuyuanp/nerdtree-git-plugin'
Plugin 'jlanzarotta/bufexplorer'
Plugin 'ervandew/supertab'
Plugin 'ctrlpvim/ctrlp.vim'
Plugin 'tacahiroy/ctrlp-funky'
Plugin 'tpope/vim-surround'
Plugin 'vimoutliner/vimoutliner'

" plugins for languages
Plugin 'groenewege/vim-less'
Plugin 'hail2u/vim-css3-syntax'
Plugin 'jtratner/vim-flavored-markdown'
Plugin 'pangloss/vim-javascript'
Plugin 'mxw/vim-jsx'

" solidity
" Plugin 'tomlion/vim-solidity'

" C/C++
Plugin 'c.vim'
Plugin 'taglist.vim'

" Dash
Plugin 'rizzatti/dash.vim'

" others
Plugin 'tomlion/vim-solidity'
Plugin 'editorconfig/editorconfig-vim'
Plugin 'scrooloose/syntastic'
Plugin 'bling/vim-airline'
```

## Install
Before you start to install the plugins, you should ensure you have `git` on your system.

Furthermore, you'll need `Vundle` to manage your vim plugins.

### Setup Vundle:

`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

### Use this vimrc file:

you can directly use link this vimrc file to your home dir:

`ln -s <THIS_REPO_DIR>/.vimrc ~/.vimrc`

And open your vim, then use `:PluginInstall` to install all the plugins

## Basic usage:

* after your open a file, hit `Tab` on your keyboard to open the `NERDTree` to view your directory structure of your repo.
* Hit `o` on your keyboard to expand a directory when your cursor is on a directory.
* Hit `o` on your keyboard to open a file for edit  when your cursor is on a file.
* Hit key combination of '\ + c + c' (hit \ first and then c twice) to comment a line
* Hit key combination of '\ + c + u' (hit \ first and then c twice) to uncomment a line
* Hit 'Ctrl + P' (at the same time) to open search file window
* Hit <Tab> to complete your insertion while there's an auto-complete hint.
* Use `:b <File name>` to open a file you once opened, which is called buffer.

## Advanced

### Colors:

I prefered to use solarized dark theme in my vim development environment.
You'll find the colors and colorscheme in the line 45/46 of `.vimrc` file.
And you'll need to link one more file:

`ln -s <THIS_REPO_DIR>/.vim/colors ~/.vim/colors`

### Font:
I prefered to use powerline fonts, if you want to use the same one as me, you can follow the instructions below:

1. `git clone git@github.com:powerline/fonts.git` clone the powerline fonts to your system.
2. `cd fonts && ./install.sh`

After that all the fonts are installed to your system.

### Item2:
I prefered to use iTerm2 as my terminal program, since you can set the fonts easily in it.
After you install the fonts to your system. open iTerm2 and go to preference by hitting "Command + ," on your keyboard.

Click "Profiles", and got to "Text", you can change the font right here.
I prefer font named "Noto Mono for Powerline" and regular with 14 as its size.

> If you want to use solarized dark theme in your terminal as well, you can go to "Colors" just beside the "Text", and choose the color presets at the bottom-right corner, use "Solarized Dark"

