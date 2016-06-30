Bash
====

* `ctrl r` - search history

Vim
===

Use `:help <letter/symbol>` from within Vim to get more information about a
certain motion/operator/text object etc., for example `:help ;` and `help dd`.


Motion
------

### Horizontal motion ###

* `h` - left
* `l` - right
* `f + <letter>` - jump to the letter
* `;` - [*add description*]
* `,` - [*add description*]


### Vertical motion ###

* `k` - up
* `j` - down 
* `gg` - go to the top
* `G` - go to the end
* `}` - [*add description*]
* `{` - [*add description*]
* `Ctrl+f` - [*add description*]
* `Ctrl+b` - [*add description*]


Macro
-----

* `q + <letter>` - start recording macro to `letter`
* `q` (while recording) - stop recording
* `@ + <letter>` - replay macro at `letter`
* `@@` - replay last replayed macro


Visual
------

* `v` - Enter character-wise visual mode
* `V` - Enter line-wise visual mode
* `Ctrl+v` - Enter block-wise visual mode
* `<Esc>` - Exit visual mode

While in visual mode, you can:
* `d` - Delete text
* `I` - Insert text (block visual mode)
* `A` - Append text (block visual mode)


Git
===

### Create a new repository ###

* `git init` - [*add description*]
* `git clone <repository>` - [*add description*]


### Show information ###

* `git status` - [*add description*]
* `git log` - [*add description*]


### Stage and commit changes ###

* `git add <files>` - [*add description*]
* `git commit` - [*add description*]
  * **Tip!** Use `git commit -v` to see exactly what you are committing.


### Remote repositories (e.g. Github) ###

* `git pull` - [*add description*]
* `git push` - [*add description*]


Tmux
====

From the command line
---------------------

* `tmux` - start new tmux session
* `tmux new -s <name>` - start a new tmux session named `<name>`
* `tmux ls` - list all sessions
* `tmux attach -t <name>` - attach session named `<name>`


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


### Splits ###

* `Ctrl+a "` - split vertically
* `Ctrl+a %` - split horizontally
* `Ctrl+a left` - switch to the pane on the left 
(works with `right`, `up`, and `down`)
