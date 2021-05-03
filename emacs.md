

# Emacs Basics

## File / Buffer commands
```
| COMMAND   Object    |   Emacs key   |  Flollow Up                        | Function name
| ------------------- | ------------- | ---------------------------------- | -----------------------
| NEW       Buffer    |   C-x b       |  <new buffer name>                 | switch-to-buffer
| SWITCH    Buffer    |   C-x b       |  <type/choose opened buffer name>  |
| OPEN      File      |   C-x C-f     |  <browse>                          |
| NEW       File      |   C-x C-f     |  <new file name>                   |
| SAVE      File      |   C-x C-s     |  <enter>                           | save-file

---
| RUN       Command   |  M-x <function name> | Run function by name:
| CANCEL    Command   |  C-g
```
## Shortcut Key Mappings:
```
| Key   | Keyboard Key  |
|------ | ------------- |  
| C     | Ctrl          |
| M     | Alt or ESC    |
```
## Modes
```
| Mode            | Key   | Command       |
| --------------- | ----- |-------------- |
| clojure-mode    | M-x   | clojure-mode  |
| major-mode      | M-x   | major-mode    |
```

## Editing
```
| DELETE  Line after  "█"    | C-k                |
| COPY                       | OS shortcut        |
| PASTE                      | OS shortcut        |
| UNDO                       | OS shortcut        |
| SEARCH                     | C-s                | Press C-s again to move to next match; C-r to go backwards 
| SELECT                     | C-space            |
| REPLACE                    | M-x replace-string |
| ---------------Navigation------------------ |
| MOVE    One Word ->       | M-f "forward"   |
| MOVE    One Word <-       | M-b "backward"  |
| MOVE    Beg of line       | C-a "first ltr" |
| MOVE    End of line       | C-e "end"       |
```

# Windows navigation
```
| COMMAND   Object    | Key   |
| ------------------- | ----- |
| SWITCH    Window    | C-x o |
| SPLIT     Screen    | C-x 2 | 3, 2, 1 to activate 3, 2, 1-window mode
| DELETE    Window    | C-x 0 |
```

# Clojure / CIDER
```
| COMMAND       Object          | Key         | Comment
| ----------------------------- | ----------- |
| EVALUATE      Last Expression | C-x C-e     |
| COMPILE       Buffer          | C-c C-k     | "Complier Kompile"
| DOCS for      Symbol under █  | C-c C-d C-d |
| GO to srs for Symbol under █  | M-. and M-, |
| SEARCH        <text>          | C-c C-d C-a | across function names and documentation.
| NAVIGATE      REPL History    | C-↑, C-↓    |
```

# Editing Clojure Code
```
PARADIT-MODE         | M-x paredit-mode (TOGGLE auto-close paredits)
WRAP         Code    | M-(          | Wraps code with "()"
MOVE         ")"     | C-→ / C-←    | Moves closing parethesis right/left including more/less code inside
NAVIGATE to  ( or )  | C-M-b,C-M-f  | Go to begidding/end of expression
```


## Links
https://www.masteringemacs.org/article/beginners-guide-to-emacs
https://www.braveclojure.com/basic-emacs/
https://github.com/clojure-emacs/cider/)
https://www.braveclojure.com/do-things/
```

