# neovimhack

vim ~/.config/nvim/init.vim

```

call plug#begin('~/.vim/plugged')
  
" leave some space in between
Plug 'preservim/nerdtree'

Plug 'mhinz/vim-startify'

Plug 'junegunn/fzf', { 'do': { -> fzf#install() } }
Plug 'junegunn/fzf.vim'

Plug 'rbgrouleff/bclose.vim'
Plug 'francoiscabrol/ranger.vim'

Plug 'preservim/nerdtree'

Plug 'iamcco/markdown-preview.nvim', { 'do': { -> mkdp#util#install() }, 'for': ['markdown', 'vim-plug']}

Plug 'junegunn/goyo.vim'


call plug#end()

" we will add keybinds below this comment.

```
