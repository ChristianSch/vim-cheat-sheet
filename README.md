# Vim cheat sheet

## Go to
### Start of line
`0`

### End of line
`$`

### Start of word
`B` or `b`

### End of word

`E` or `e`

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
