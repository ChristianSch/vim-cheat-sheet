# Vim cheat sheet
Note: you can combine almost everything with movements. Like combine `v` (visual) with `e`
(end of word) to select the text from the current cursor position to the end of the word.

Pro tip:  `ZZ` instead of `<esc> + :wq`.

## Go to
### Start of line
`0`

### End of line
`$`

### Start of word
`B` or `b`

### End of word
`E`or `e`

### Start of file
`gg`

### End of file
`G`

## Cut & Copy
### Start “visual mode”
* `v` and select chars
* `V` for whole line

### Copy
* `y` for selected chars
* `yy` or `Y` for whole line
* `2yy` for two lines (`nyy` for n lines)

### Cut
* `d`

### Paste
* `P` before pointer
* `p` after pointer

## Delete
### Delete word under cursor
* `dw`: delete word
* `daw`: delete around word
* `caw`: delete around word, enter edit mode
* `diw`: delete in word

### Delete rest of line
`d$` or `D`

### Delete everything on the line to the cursor
`d0`

## Insert line
This only works in 'normal mode' and then enters the 'edit mode'.

### Before cursor
`O`

### After cursor
`o`

## Indentation
* `>>`: indent one block to the right
* `<<`: indent one block to the left
* `4>>`: indent four lines one block to the right

## Split view
* `:sp $file` to open a file in another split view
* `ctrl + w s` to split the current buffer horizontally
* `ctrl + w v` to split the current buffer vertically

* `ctrl + w w` to change split buffer
* `ctrl + w up` to select the buffer on top of the current one
* `ctrl + w down` " beneath the current one
* `ctrl + w left` " on the left of the current one
* `ctrl + w right` " on the right of the current one

* `ctrl + w q` close current split buffer

## Folding
* `za` toggles current fold

## Repeat
* `.` repeats the last command (if applicable)
