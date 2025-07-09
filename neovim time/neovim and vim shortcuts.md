**Modes:** normal mode, `:` to use command mode, `I` to use insert mode(typing is all in this mode)

`vim` to make a new vim instance
`vim {filename.ext}` to open a file in vim

* * *

> [!info] Pro tip
> - Commands can be combined to perform in order (like `:wq` to save and quit)
> - You can perform Linux commands while in command mode in vim 

#### Vim basics
- `:q` to exit vim
- `:w` to write file (for saving)
- `:r {filename.ext}` to insert content of specified file into current buffer
- `U` to undo changes
- `0` to move cursor to beginning of line
- `$ (Shift + 4)` to move cursor to end of line w/o switching to insert mode

#### While in normal mode
- `Shift + A` to enter insert mode & move cursor to end of current line
- `X` to delete a character
- `D` twice in quick succession to delete an entire line
- `H, J, K, L` to move cursor left, down, up, right (just helps with touch typers)

---

vim progress:
- [x] exit vim
- [x] edit in vim
- [x] save file in vim
