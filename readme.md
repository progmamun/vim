# vim-notes

# About_Vim

- Vim is a highly configurable text editor built to make creating and changing any kind of text very efficient. It is included as "vi" with most UNIX systems and with Apple OS X. Vim is a free and open-source, screen-based text editor program. It is an improved clone of Bill Joy's vi. Vim's author, Bram Moolenaar, derived Vim from a port of the Stevie editor for Amiga and released a version to the public in 1991.
  <img src="https://user-images.githubusercontent.com/67066348/161417121-26a00e12-ff4c-4e4b-a28c-f4b563ea7e35.png" alt="Vimlogosvg" width="200"/>

---

# Global

- `:h[elp] keyword` -open help for keyword
- `:sav[eas] file` -save file as
- `:clo[se]` -close current pane
- `:ter[minal]` -open a terminal window
- `K` -open man page for word under the cursor

# Cut and Paste

- `yy` -yank (copy) a line
- `2yy` -yank (copy) 2 lines
- `yw` -yank(copy) the characters of the word from the cursor position to the start of the next word.
- `yiw` -yank(copy) word under the cursor
- `yaw` -yank(copy) word under the cursor and the space after or before it
- `y$` or `Y` -yank(copy) to end of line
- `p` -put (paste) the clipboard after cursor
- `P` -put(paste) before cursor
- `gp` -put(paste) the clipboard after cursor and leave cursor after the new text
- `gP` -put(paste) before cursor and leave cursor after the new text
- `dd` -delete(cut) lines
- `2dd` -delete(cut) 2 lines
- `dw` -delete(cut) the characters of the word from the cursor position to the start of the next word
- `diw` -delete (cut) word under the cursor and the space after or before it
- `daw` -delete(cut) word under the cursor and the space after or before it
- `d$` or `D` -delete (cut) to the end of the line
- `x`- delete (cut) character
