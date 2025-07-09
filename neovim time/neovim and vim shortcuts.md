**Modes:** normal mode, `:` to use command mode, `I` to use insert mode(typing is all in this mode), `V` to use visual mode

`vim` to make a new vim instance
`vim filename.ext` to open a file in vim

* * *

> [!tip] Pro tip
> - Commands can be combined to perform in order (like `:wq` to save and quit)
> - You can perform Linux commands while in command mode in vim with
>   `:! your_command_here` for some reason

#### Commands
- `:q` to exit vim
- `:w` to write file (for saving)
- `:r filename.ext` to insert content of specified file into current buffer
- `:e filename.ext` to edit specified file in a new buffer
- `:bp` to move to previous buffer
- `:bn` to move to next buffer
- `:enew` to create an empty buffer

#### While in normal mode
- `Shift + A` to enter insert mode & move cursor to end of current line
- `X` to delete a character
- `D` twice in quick succession to delete an entire line
- `H, J, K, L` to move cursor left, down, up, right (just helps with touch typers)
- `U` to undo changes
- `0` to move cursor to beginning of line
- `$ (Shift + 4)` to move cursor to end of line w/o switching to insert mode
- `: {line_number}` to move cursor to said line

#### Visual mode
- Position the cursor, then press `V` to begin selecting text
- Move cursor around to select text
- Press `Y` to yank (copy), will also exit visual mode
- Press
---

vim progress:
- [x] exit vim
- [x] edit in vim
- [x] save file in vim
