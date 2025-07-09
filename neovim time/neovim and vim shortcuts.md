**Modes:** normal mode, `:` to use command mode, `I` to use insert mode(typing is all in this mode), `V` to use visual mode

`vim` to make a new vim instance
`vim filename.ext` to open a file in vim
`vim +{line_number} filename.ext` to start vim at said line number

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
- `:bd` to delete current buffer
- `:enew` to create an empty buffer
- `:split filename.ext` to create a new split with file (can be replaced with `:sp`)
- `:vsplit` or `:vsp` or `:vs` to create vertical split
- `Ctrl + W(2x)` to move to next split
#### While in normal mode
- `Shift + A` to enter insert mode & move cursor to end of current line
- `Shift + W` to move between characters
- `X` to delete a character
- `D` twice in quick succession to delete an entire line and copy into paste buffer
- `H, J, K, L` to move cursor left, down, up, right (just helps with touch typers)
- `U` to undo changes
- `0` to move cursor to beginning of line
- `$ (Shift + 4)` to move cursor to end of line w/o switching to insert mode
- `: {line_number}` to move cursor to said line
- Press `P` to put (paste) after selecting in visual mode
- `G` twice in quick succession to go to beginning of file
- `Shift + G` to go to end of file

#### Visual mode
- Position the cursor, then press `V` to begin selecting text
- Press `Y` to yank (copy), will also exit visual mode
- Switch to command mode while having selected text to process it (like alphabetizing with `sort ui`)

#### Random tips
1) Find and replace
	- `%s/{text_find}/{text_replace}/g`
2) Enable line numbers
	- `:set number`
3) Disable line number
	- `:set nonumber`
4) `:badd filename.ext` to add buffer without switching to it
5) Open vim with several files at the same time
6) 

#### Configure Vim
- `vim .vimrc`
- `"` at beginning of line to comment


---

vim progress:
- [x] exit vim
- [x] edit in vim
- [x] save file in vim
