# MyCheatSheet
A cheat sheet for general software installations and other frequently occurring problem

## Minimal vim configuration
[Copied from here](https://github.com/enocom/vim-config/blob/master/vimrc)
Put the following lines in .vimrc

set autowrite                  " write before ':make' commands<br>
set wildmenu                   " show possible completions on command line<br>
set backspace=indent,eol,start " configure backspace behavior<br>
set textwidth=80               " set width of all text<br>
set noswapfile                 " disable swap files<br>
set nowb                       " disable writing backup<br>
set smartcase                  " ignore case if lower, otherwise match case<br>
set splitbelow                 " split panes on the bottom<br>
set splitright                 " split panes to the right<br>
set autoindent                 " indent line based on previous line<br>
set smartindent                " add extra indent based on previous line<br>
set shiftwidth=4               " assume 4 spaces for a tab<br>
set expandtab                  " expand those tabs to spaces<br>
set tabstop=4                  " number of spaces a tab counts for in file<br>
set softtabstop=4              " number of spaces a tab counts for editing<br>
set smarttab                   " translate tabs into shiftwidth worth of spaces<br>

## Installing required cuda drivers and library to run deeplearning models on gpu
1. Install cuda driver using the script given here https://cloud.google.com/compute/docs/gpus/add-gpus
2. Download libcudnn run time and dev .deb files
3. sudo dpkg -i install &lt;libcudnn run time library>
4. sudo dpkg -i install &lt;libcudnn dev library>

## Setting virtual environment for python3

1. sudo apt-get install virtualenv -y
2. virtualenv -p python3 venv

## Installing python3-dev
sudo apt-get install python3-dev



