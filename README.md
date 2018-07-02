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

> Pressing just the motion while in Normal mode without an operator will move the cursor as specified.
