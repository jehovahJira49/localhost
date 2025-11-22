# Neovim Cheatsheet

## Undo/Redo
- `u` - Undo
- `C-r` - Redo the last undo change

## Move Word by Word
- `w`, `b`, `e`, `ge` - Move by word
- `W`, `B`, `E`, `gE` - Move by WORD (whitespace-separated)

## Move to a Specific Character
- `f{character}` - Move forward to character (in the line)
- `;` - Next occurrence
- `,` - Previous occurrence
- `t{character}` - Move to just in front of the character in the line

## Move Horizontally (Extreme)
- `0` - First character of line
- `^` - First non-blank character of line (useful for Python indentations)
- `$` - End of line
- `g_` - Non-blank character at the end of the line

## Move Vertically (Extreme)
- `k`, `j` - Move vertically up/down
- `}` - Jump entire paragraph downwards
- `{` - Jump entire paragraph upwards
- `C-d` - Move down half a page
- `C-u` - Move up half a page
- `gg` - Top of file
- `G` - End of file
- `{line}gg` - Specific line of file

## Operators
- `d` - Delete
- `c` - Change
- `y` - Yank (copy)
- `p` - Paste
- `g~` - Switch case
- `>` - Shift right
- `<` - Shift left
- `=` - Format

### Line Operations
- `dd` - Delete line
- `cc` - Change a line
- `yy` - Yank (copy) a line
- `g~~` - Switch case of line
- `>>` - Shift line right
- `<<` - Shift line left

### From Cursor to End of Line
- `D` - Delete from cursor to the end of line
- `C` - Change from cursor to the end of line
- `Y` - Yank from cursor to the end of line
- `P` - Paste before cursor

## Repeat
- `.` - Repeat last change

## Insert Modes
- `I` - Insert mode at the beginning of line
- `A` - Insert mode at the end of line
- `o` - Insert new line below the current line and go to insert mode
- `O` - Insert new line above the current line and go to insert mode

## Insert Mode Shortcuts
- `C-H` - Delete last character
- `C-W` - Delete last word
- `C-U` - Delete last line

## File Operations
- `:edit {file}` or `:e {file}` - Create or edit a file
- `:w` - Save file
- `:q` - Close file
- `:w!` - Force save file
- `:wall` - Save all files
- `:wqall` - Save and close all files

## Splitting Windows
- `:sp` - Open file in a horizontal split
- `:vsp` - Open file in a vertical split
- `C-W S` - Open same file in horizontal split
- `C-W V` - Open same file in vertical split
- `C-W h` - Move to the split to the left
- `C-W j` - Move to the split below
- `C-W k` - Move to the split above
- `C-W l` - Move to the split to the right
