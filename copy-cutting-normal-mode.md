# Copying and cutting in normal mode

In normal mode, one can copy (yank) with y{motion}, where {motion} is a Vim motion. For example, yw copies to the beginning of the next word. Other helpful yanking commands include:

- yy or Y – yank the current line, including the newline character at the end of the line
- y$ – yank to the end of the current line (but don't yank the newline character); note that many people like to remap Y to y$ in line with C and D
- yiw – yank the current word (excluding surrounding whitespace)
- yaw – yank the current word (including leading or trailing whitespace)
- ytx – yank from the current cursor position up to and before the character (til x)
- yfx – yank from the current cursor position up to and including the character (find x)

Cutting can be done using d{motion}, including:

- dd - cut the current line, including the newline character at the end of the line

To copy into a register, one can use "{register} immediately before one of the above commands to copy into the register {register}. See pasting registers for more information on register syntax.

Quelle: [https://vim.fandom.com/wiki/Copy,_cut_and_paste?action=edit&section=1&veaction=edit](https://vim.fandom.com/wiki/Copy,_cut_and_paste?action=edit&section=1&veaction=edit)
