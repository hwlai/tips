Tmux
====

From the command line
---------------------

* `tmux` - start new tmux session
* `tmux new -s <name>` - start a new tmux session named `<name>`
* `tmux ls` - list all sessions
* `tmux attach -t <name>` - attach session named `<name>`
* `tmux kill-session -t <name>` - kill session named `<name>`

From within tmux
----------------

Here we assume that the tmux key is `Ctrl+a`.


### Sessions ###

* `Ctrl+a d` - deattach session
* `Ctrl+a $` - rename current session


### Windows ###

* `Ctrl+a c` - create a new window
  * To close a window, simply exit the shell (with `exit` or `Ctrl+d`).
* `Ctrl+a 1` - switch to window 1 (works with `2`, ..., `9`, and `0`)
* `Ctrl+a p` - switch to previous window
* `Ctrl+a n` - switch to next window
* `Ctrl+a ,` - rename current window
* `Ctrl+a &` - kill current window

### Splits ###

* `Ctrl+a "` - split vertically
* `Ctrl+a %` - split horizontally
* `Ctrl+a left` - switch to the pane on the left 
(works with `right`, `up`, and `down`)
* `Ctrl+a  o` - switch between panes
* `Ctrl+a  x` - kill current pane
