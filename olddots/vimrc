call plug#begin('~/.vim/plugged')
  Plug 'scrooloose/nerdtree', { 'on':  'NERDTreeToggle' }
  Plug 'tpope/vim-surround'
  Plug 'tpope/vim-commentary'
  Plug 'tpope/vim-fugitive'
  Plug 'scrooloose/syntastic'
  Plug 'rafi/awesome-vim-colorschemes'
  Plug 'vim-airline/vim-airline'
  Plug 'vim-airline/vim-airline-themes'
  Plug 'SirVer/ultisnips'
  Plug 'yanqd0/snippets-for-vim'
  Plug 'hlissner/vim-ultisnips-snippets'
call plug#end()

let g:UltiSnipsExpandTrigger="<tab>"
let g:UltiSnipsJumpForwardTrigger="<c-b>"
let g:UltiSnipsJumpBackwardTrigger="<c-z>"

let g:UltiSnipsSnippetsDir = "~/.vim/snips/"

let g:airline_theme='powerlineish'
colorscheme molokayo

nnoremap <C-J> <C-W><C-J>
nnoremap <C-K> <C-W><C-K>
nnoremap <C-L> <C-W><C-L>
nnoremap <C-H> <C-W><C-H>

" autocmd Filetype rmd map <F5> :!echo<space>"require(markdown);<space>render('<c-r>%')"<space>\|<space>R<space>--vanilla<enter>

set showtabline=2
set wildmenu
set path+=**
set nowrap
set splitbelow splitright

" show existing tab with 2 spaces width
set tabstop=2
" when indenting with '>', use 2 spaces width
set shiftwidth=2
" On pressing tab, insert 2 spaces
set expandtab

set number
set relativenumber
set nocompatible
set showcmd

syntax enable
filetype plugin on

" Fuzzy find
set path+=**
set wildmenu

" ctags ctrl+] to jump, prepend with g to see every occurence. ctrl+t to jump
" back
nnoremap <F1> :NERDTreeToggle<CR>
command! Maketags !ctags -R .

" file browsing
" let g:netrw_banner=0
" let g:netrw_browse_split=4
" let g:netrw_altv=1
" let g:netrw_liststyle=3

" snippets
" blueprint:
" nnoremap ,html :-1read $HOME/.vim/.skeleton.html<CR>3jwf>a
nnoremap \html :-1read $HOME/.vim/.skeleton.html<CR>3jwf>a
nnoremap \is :-1read /home/vagrant/.vim/.skeleton.server.c<CR>
