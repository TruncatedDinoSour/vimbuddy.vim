# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/vimbuddy.vim>
# VimBuddy.vim

<details>
  <summary>Click to preview</summary>

| Type    | Image                                                                                                              |
| ------- | ------------------------------------------------------------------------------------------------------------------ |
| Normal  | ![normal](https://github.com/TruncatedDinoSour/vimbuddy.vim/assets/71613062/5dea5930-e495-44d2-83d0-d29989f72e1f)  |
| Error   | ![error](https://github.com/TruncatedDinoSour/vimbuddy.vim/assets/71613062/adcb84d5-35b3-4f4c-bc05-46d4c4385548)   |
| Warning | ![warning](https://github.com/TruncatedDinoSour/vimbuddy.vim/assets/71613062/a9bdbefb-a7cd-4f6d-b2a4-7c18ea94f30a) |
| Message | ![message](https://github.com/TruncatedDinoSour/vimbuddy.vim/assets/71613062/5e8236b5-16aa-4214-9e90-6b4786e0969b) |

</details>

> Puts a smiley on your status line. Nose will rotate on <Left> and <Right>
> Will frown on errors and warnings

# Triggers

A trigger is a variable in the `g:` scope that
can trigger a certain reaction in VimBuddy

Triggers follow this scheme: `g:vimbuddy_t<level>`,
all current triggers:

-   `g:vimbuddy_terr` -- Triggers `error` face
-   `g:vimbuddy_twarn` -- Triggers `warning` face
-   `g:vimbuddy_tmsg` -- Triggers `message` face

These variables can have any value, you can `unlet` them
to release the effect

# Installation

-   VimPlug:

```vim
Plug 'TruncatedDinosour/vimbuddy.vim'
```
