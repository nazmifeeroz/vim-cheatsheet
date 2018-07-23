# VIM Cheatsheet

### Moving the cursor

| Navigating | Description |
| :--------: | :---------: |
|    `k`     |     UP      |
|    `j`     |    DOWN     |
|    `h`     |    LEFT     |
|    `l`     |    RIGHT    |

|    saving     |            Description             |
| :-----------: | :--------------------------------: |
|    `<ESC>`    |  Make sure you are in Normal mode  |
| `:q! <ENTER>` | Exiting VIM discarding any changes |
|     `:wq`     |        Save a file and exit        |

| Edit Text |              Description              |
| :-------: | :-----------------------------------: |
|    `x`    | Delete the character under the cursor |
|    `i`    |              Insert text              |
|    `a`    |            To append text             |

| Delete |            Description             |
| :----: | :--------------------------------: |
|  `dw`  |           delete a word            |
|  `d$`  |   delete to the end of the line    |
|  `de`  | Delete including the last charater |
|  `dd`  |       to delete a whole line       |
| `2dd`  |        to delete two lines         |
| `d2w`  |  deletes with the number of words  |

> Pressing just the motion while in Normal mode without an operator will move the cursor as specified.

| Motion |                     Description                      |
| :----: | :--------------------------------------------------: |
|  `2w`  |          move the cursor two words forward           |
|  `3e`  | move the cursor to the end of the third word forward |
|  `0`   |            move to the start of the line             |

> Undo command

| Undo |                     Description                      |
| :----: | :--------------------------------------------------: |
| u | Undo previous actions. (lowercase u) |
| U | Undo all the changes on a line. (capital U) |
| CTLR-R | Undo the undo's |

> The PUT command. `p` to put previously deleted text after the cursor. `dd` to delete a line. `p` to add the deleted line.

| Replace | Description |
| :----: | :--------------------------------------------------: |
| `r` | to replace the character at the cursor with x |
| `ce` | to change until the end of a word |
| `c` + motion | used with the same motion as delete |

