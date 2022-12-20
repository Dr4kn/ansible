" yank to global clipboard
set clipboard=unnamedplus
" relative line number
set relativenumber
" ignore case when searching
set ignorecase
" Show matchin brackets when indicator is over them
set showmatch
" Hom many tenths of a second to blink when matching brackets
set mat=2
" syntax highlighting
set syntax
" Set regular expression engine automatically
set regexpengine=0

" Enable 256 colors palette in Gnome Terminal
if $COLORTERM == 'gnome-terminal'
    set t_Co=256
endif
try
    colorscheme desert
catch
endtry

" Use spaces instead of tabs
set expandtab
" indents further with tabs depending on context
set smarttab
" 1 tab == 4 spaces
set shiftwidth=4
set tabstop=4

noremap <Leader>y "*y
noremap <Leader>p "*p
noremap <Leader>Y "+y
noremap <Leader>P "+p
noremap <C-d> <C-d>zz
noremap <C-u> <C-u>zz

" Visual mode pressing * or # searches for the current selection
" Super useful! From an idea by Michael Naumann
vnoremap <silent> * :<C-u>call VisualSelection('', '')<CR>/<C-R>=@/<CR><CR>
vnoremap <silent> # :<C-u>call VisualSelection('', '')<CR>?<C-R>=@/<CR><CR>