# Vim Tutorial
Throw your mouse away, and code efficiently
[TOC]

## Download Vim Package in VScode
*    Open VScode
*    Ctrl + Shift + x
*    Type Vim, download the package and restart your VScode
![](https://i.imgur.com/SYvpBCq.png)
*    Open any code you have, and make sure you have another copies for this file.

## Open the file in linux OS
*    vim [filename]

## Exit from the vim
```bash=
:q + Enter     #quit, if you modified the file, you will get warning
:q! + Enter    #quit and not save
:wq + Enter    #save and quit
:w + Enter     #save the file and not quit
```

## Command Mode
When you open the file in VScode or linux OS by typing vim [filename], you're now get in the command mode, in this mode, you can't edit your code, but you can move your cursor.

### Moving Cursor
```bash=
j            #go down
k            #go up
l            #go right
h            #go left
shift + g    #go to bottom
gg           #go to top
}            #go down next code block
{            #go up next code block

#using prefix number to repeat the command, ex:
20j          #go down 20 lines
30l          #go right 30 times
10}          #go down 10 code blocks
```

### Delete whole Line
```bash=
dd        #delete whole line
u         #undo
Ctrl + R  #undo "undo" command
```

### Copy code
```bash=
yy        #copy the line where cursor located
p         #paste the line you copied (Note you will paste the code below your cursor)
```


## Insert Mode
After moving your cursor to where you want to edit your code, press i to entry the Insert Mode, and now you can edit your code.
```bash=
i    #from command mode to insert mode
esc  #from insert mode to command mode
```