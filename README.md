# Vim Cheat Sheet 🔥

A simple cheat sheet to help you become slightly more functional in Vim than `i` + `esc` + `:wq`.

## Commands

### Move Around

| Key(s)       | Action                                  |
| ------------ | --------------------------------------- |
| `h`          | left                                    |
| `j`          | down                                    |
| `k`          | up                                      |
| `l`          | right                                   |
| `0`          | go to start of line                     |
| `^`          | go to first non-black character of line |
| `$`          | go to end of line                       |
| `gg`         | go to first line                        |
| `G`          | go to last line                         |
| `:5`         | go to line n                            |
| `5G`         | got to line 5                           |
| `Ctrl` + `f` | move forward one screen                 |
| `Ctrl` + `b` | move backward one screen                |

### Insert & Replace

| Key(s) | Action                                 |
| ------ | -------------------------------------- |
| `i`    | insert before the cursor               |
| `I`    | insert at the beginning of the line    |
| `a`    | append after the cursor                |
| `A`    | append at the end of the line          |
| `o`    | open a new line below the current line |
| `O`    | open a new line above the current line |
| `r`    | replace a character                    |
| `cw`   | change a word                          |
| `cc`   | change a line                          |
| `esc`  | exit insert mode                       |

### Cut, Copy & Paste

| Key(s) | Action                                                |
| ------ | ----------------------------------------------------- |
| `yy`   | yank (copy) a line                                    |
| `5yy`  | yank 5 lines                                          |
| `yw`   | yank a word from the cursor position to the next word |
| `yiw`  | yank inner word (with no spaces)                      |
| `x`    | delete (cut) a character                              |
| `dd`   | delete a line                                         |
| `5dd`  | delete 5 lines                                        |
| `dw`   | delete a word                                         |
| `p`    | paste after cursor                                    |
| `P`    | paste before cursor                                   |

### Undo, Redo & Repeat

| Key(s)       | Action                  |
| ------------ | ----------------------- |
| `u`          | undo                    |
| `Ctrl` + `r` | redo                    |
| `.`          | repeat previous command |

### Search, Find & Replace

| Key(s)          | Action                                                |
| --------------- | ----------------------------------------------------- |
| `/pattern`      | forward search for pattern                            |
| `n`             | repeat last search                                    |
| `N`             | repeat last search in the opposite direction          |
| `:noh`          | shut off highlighted search results until next search |
| `:%s/old/new/`  | replace on the current line                           |
| `:%s/old/new/g` | replace globally throughout the document              |

### Use Tabs

| Key(s)             | Action                             |
| ------------------ | ---------------------------------- |
| `:tabnew filename` | open file in a new tab             |
| `:tabdo command`   | run a command on all tabs          |
| `:tabclose`        | close the current tab              |
| `:tabonly`         | close all tabs but the current one |
| `gt`               | move to next tab                   |
| `gT`               | move to previous tab               |
| `5gt`              | move to tab 5                      |

### Save & Close

| Key(s) | Action                                    |
| ------ | ----------------------------------------- |
| `:w`   | write (save)                              |
| `:wq`  | write (save) and quit (close)             |
| `:wq!` | force write (save) and quit (close)       |
| `:q`   | quit (close)                              |
| `:q!`  | force quit (close) without saving changes |

### Global

| Key(s)             | Action                         |
| ------------------ | ------------------------------ |
| `:help keyword`    | get help on a command or topic |
| `:set keyword`     | toggle editor option           |
| `:edit filename`   | open file to edit              |
| `:saveas filename` | save file as                   |

## Also Included

- `.vimrc`: a lightweight Vim configuration
- `.vim`: contains [An Old Hope](https://github.com/j-tom/vim-old-hope) colour scheme for Vim

## References

- A great (more detailed) Vim cheat sheet: https://vim.rtorr.com
- An Old Hope colour scheme: https://github.com/j-tom/vim-old-hope
