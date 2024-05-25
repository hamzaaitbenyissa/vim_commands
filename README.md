# Vim Cheat Sheet

Vim is a powerful text editor with a rich set of commands. Here are some of the most commonly used commands to get you started:

## Basic Commands

### Navigation
- `h` : Move left
- `j` : Move down
- `k` : Move up
- `l` : Move right
- `w` : Move to the beginning of the next word
- `b` : Move to the beginning of the previous word
- `0` : Move to the beginning of the line
- `$` : Move to the end of the line
- `gg` : Move to the beginning of the file
- `G` : Move to the end of the file

### Insert Mode
- `i` : Insert before the cursor
- `I` : Insert at the beginning of the line
- `a` : Insert after the cursor
- `A` : Insert at the end of the line
- `o` : Open a new line below the current line
- `O` : Open a new line above the current line
- `Esc` : Exit insert mode

### Selecting Text
- `v` : Start visual mode (character-wise selection)
- `V` : Start visual line mode (select whole lines)
- `Ctrl-v` : Start visual block mode (select a block of text)
- `ggVG` : Select all text in the file

### Editing Text
- `y` : Yank (copy) selected text
- `yy` : Yank the current line
- `p` : Paste after the cursor
- `P` : Paste before the cursor
- `d` : Delete selected text
- `dd` : Delete the current line
- `x` : Delete the character under the cursor
- `u` : Undo
- `Ctrl-r` : Redo
- `:%d` : Delete all text in the file

### Searching
- `/pattern` : Search for `pattern`
- `n` : Repeat search in the forward direction
- `N` : Repeat search in the backward direction
- `:%s/old/new/g` : Replace all occurrences of `old` with `new` in the file

### File Operations
- `:w` : Save the file
- `:q` : Quit Vim
- `:wq` : Save and quit
- `:q!` : Quit without saving
- `:e filename` : Open a file
- `:set number` : Show line numbers
- `:set nonumber` : Hide line numbers

### Advanced Commands
- `:x` : Save and quit (same as `:wq`)
- `:%y` : Yank (copy) the entire file
- `:%d` : Delete the entire file
- `:r filename` : Read and insert the content of `filename` at the cursor position
- `:!command` : Execute an external command
- `Ctrl-g` : Display the file name and cursor position

## Tips
- Use `.` to repeat the last command.
- Use `Ctrl-o` to go back to the previous cursor position in normal mode.
- Use `Ctrl-i` to go forward to the next cursor position in normal mode.
- Use `:help command` to get help on a specific command.

This cheat sheet covers the most essential commands to get you started with Vim. For a more comprehensive guide, refer to the [official Vim documentation](https://www.vim.org/docs.php).
