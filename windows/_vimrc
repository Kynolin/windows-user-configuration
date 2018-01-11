" Windows vimrc.
" This is NOT the same, or as customized, as my Linux vimrc.

" Make sure plugin managers work. Shouldn't be needed with custom user vimrc and no plugins. Also will break vim -C, but I'm using it anyways.
set nocompatible

" Remove default Windows stuff.
"source $VIMRUNTIME/vimrc_example.vim
"The above file had tw=78 which created automatic line breaks and odd behavior
"source $VIMRUNTIME/mswin.vim
"behave mswin

" Make VIM behave like Linux.
behave xterm
set backspace=indent,eol,start
" Don't automatically create line breaks. Shouldn't be needed with above options.
"set tw=0

" Make VIM use the OS clipboard with yank/paste.
" Windows
set clipboard=unnamed
" Linux
"set clipboard=unnamedplus


" Make it pretty.
" Syntax highlighting.
syntax on

" Font
" Linux
"set guifont=DejaVu\ Sans\ Mono\ 12
" Windows
set guifont=DejaVu_Sans_Mono:h12:cANSI
colorscheme slate

" Relative Line Numbers
set rnu
