# VimBuddy.vim

[![Preview](https://asciinema.org/a/rhNFz5lLaDxKpatZQPbYqnaXQ.svg)](https://asciinema.org/a/rhNFz5lLaDxKpatZQPbYqnaXQ)

> Puts a smiley on your status line. Nose will rotate on <Left> and <Right>
> Will frown on errors and warnings

# Triggers

A trigger is a variable in the `g:` scope that
can trigger a certain reaction in VimBuddy

Triggers follow this scheme: `g:vimbuddy_t<level>`,
all current triggers:

- `g:vimbuddy_terr` -- Triggers `error` face
- `g:vimbuddy_twarn` -- Triggers `warning` face
- `g:vimbuddy_tmsg` -- Triggers `message` face

These variables can have any value, you can `unlet` them
to release the effect

# Installation

- VimPlug:

```vim
Plug 'TruncatedDinosour/vimbuddy.vim'
```
