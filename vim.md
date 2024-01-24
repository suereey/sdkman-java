# Vim
[Install vim](https://formulae.brew.sh/formula/vim)
```
brew install vim
```

More resources: Vim treatsheet

## Open/Quit/Insert

Open a file (create if not exist):
```
vi test.txt
```

Write in a file (insert mode):
- Use ```i/a/o``` to insert mode
    ```
    ; In 12345, if cursor at 3, and further type A
    i       ; 12A345
    a       ; 123A45
    shift+i ; Capital I, A12345
    o       ; 12334 open a new line below
    shift+o ; O, open a new line above

    ```
- Use ```esc``` to normal mode

Quit a file:
```
:q      ; quit
:q!     ; ignore all changes and quit
:wq     ; write and quit
:w      ; write and save not quit
```


set line number
```
:set number
:set relativenumber
```
related key binding: ove cursor within the range
```
5 downerror ; move cursor 5 line down
5 j         ; move curser 5 line down
```

## Others 
```
h       ; left
l       ; right
j       ; down
k       ; up
```


note that ```:!``` in vim, is a terminal command. for example
```
:! ls
```

open file with previous setting (for example, show line number)

```
vi ~/.vimrc     ; vimrc is a file name, put settings here
vi test.txt     ; then open test.txt, it will contain settings
```

```
set mouse=a     ; set the mouse to active

```

## Others
```
u       ; normal mode: undo
crl + r ; normal mode: redo
3u      ; 3 undo
```

visual mode
```
v
d       ; delete
```
