phpironman colorscheme for vim
==============================

![Screenshot](https://www.dropbox.com/s/6aj48q6u1xnua7z/Screenshot%202015-04-14%2018.48.23.png?dl=0)

Instructions
------------

Put phpironman.vim in your `~/.vim/colors` and run `:colors phpironman`

MacVim configuration suggestion:

```vim
if has('gui_macvim')
    set showtabline=2
    set imdisable
    set transparency=0
    set guioptions-=m
    set guioptions-=M
    set antialias
    set guifont=Monaco:h14
elseif has('gui_gtk2') 
    set guifont=Bitstream\ Vera\ Sans\ Mono\ 10
    "set gfn=ProggyCleanTT\ CE\ 12
    "set gfn=ProggyCleanTT_CE:h16
    "set gfn=ProggySquareTT\ 12
    "set gfn=Crisp\ 12
elseif has('gui_win32') 
    "set gfn=Consolas\ 10
    set guifont=Courier\ New:h12
endif
```
