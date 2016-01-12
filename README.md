## About 

An awesome vim configuration that I use every day.

## Installation

To install it easily, please run:

`curl -sS
https://raw.githubusercontent.com/idvoretskyi/vim_idv/master/install.sh | bash`

## Updating existing installation

Simply run the following command:

`https://raw.githubusercontent.com/idvoretskyi/vim_idv/master/update.sh | bash`

## Plugin Management
The full list of plugins one may find in `'~/.vim/plugins.vim'` file. To add any
new plugin, simply add it to that file.

Example: I'd like to add the NERD tree plugin.
I have to simply run:

`echo "Plugin 'scrooloose/nerdtree' >> ~/.vim/plugins.vim && vim +PluginInstall +qall`.

Detailed information about Plugin installation one may find in [Vundle.vim](https://github.com/VundleVim/Vundle.vim) documentation.

# Bundled plugins

In my vim distribution the following Plugins are used:

* [christoomey/vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator):
  Seamless navigation between tmux panes and vim splits

Bundle 'JarrodCTaylor/vim-shell-executor'
Bundle 'andviro/flake8-vim'
Bundle "MarcWeber/vim-addon-mw-utils"
Bundle "tomtom/tlib_vim"
Bundle "garbas/vim-snipmate"
Bundle "honza/vim-snippets"
Bundle 'chase/vim-ansible-yaml'
Bundle 'scrooloose/nerdtree'
Bundle 'klen/python-mode'
Bundle 'davidhalter/jedi-vim'
Bundle 'vim-scripts/nginx.vim'
Bundle 'toupeira/vim-desertink'
Bundle 'tomasr/molokai'
Bundle 'tpope/vim-eunuch'
Bundle 'tpope/vim-fugitive'
Bundle 'rosenfeld/conque-term'
Bundle 'jistr/vim-nerdtree-tabs'
Bundle 'scrooloose/syntastic'
Bundle 'majutsushi/tagbar'
Bundle 'sickill/vim-monokai'
Bundle 'w0ng/vim-hybrid'
Bundle 'scrooloose/nerdcommenter'
Bundle 'bling/vim-airline'
Bundle 'Conque-Shell'
Bundle 'Xuyuanp/nerdtree-git-plugin'
Bundle 'rodjek/vim-puppet'
Bundle 'vim-ruby/vim-ruby'
Bundle 'godlygeek/tabular'
Bundle 'altercation/vim-colors-solarized'
Bundle 'fatih/vim-go'
Bundle 'vim-jp/vim-go-extra'
Bundle 'rjohnsondev/vim-compiler-go'




