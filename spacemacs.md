# Spacemacs
A cheatsheet for me whilst learning spacemacs shortcuts/commands with evil mode.

## General
### Spacemacs
| Command  | Description                      |
|----------|----------------------------------|
| SPC f f  | find file                        |
| SPC f s  | save file                        |
| SPC b b  | switch buffers                   |
| SPC TAB  | previous buffer, like q in cs <3 |
| quick fd | exit insert mode                 |

## Window
### Spacemacs
| Command                  | Description                                   |
|--------------------------|-----------------------------------------------|
| SPC w d                  | delete current window( in emacs called frame) |
| SPC w h/j/k/l//arrowkeys | move between windows                          |
| SPC w v                  | Open new window vertically                    |
| SPC w V                  | Opens new window vertically AND FOCUSES       |
| SPC w TAB                | cycle windows, probably like C-x o            |
| SPC w m                  | Maximize current windom                       |

## Searching, jumping, moving
### Spacemacs
| Command    | Description                         |
|------------|-------------------------------------|
| SPC j l    | jump to line numbers OR via letters |
| SPC s s    | search                              |
| SPC s e    | search & edit marked                |

### Evil
| Command    | Description    |
|------------|----------------|
| <line> g g | jump to line   |
| g g        | jump to top    |
| G          | jump to bottom |
| f `<char>` | find next char |
| F `<char>` | find previous  |


## Editing, replacing, surrounding
### Evil
| Command                       | Description                                              |
|-------------------------------|----------------------------------------------------------|
| c s `<char>` `<opening char>` | change surrounding char to char with whitespace, c s ( [ |
| c s <char> <closing char>     | change surrounding char to char, c s ( ]                 |
| y s i w `<char>`              | surround word with char                                  |
| y s s `<char>`                | surround line with char                                  |
| d d                           | delete line                                              |
| c c                           | change line                                              |

## Other
| Command | Description       |
|---------|-------------------|
| SPC m   | major mode things |
