Bash
====

* `ctrl r` - search history


Git
===

Workflows
---------

### Commit changes and push to Github ###

1. `cd` to the directory that contains the repository.

  Example: `cd ~/.dotfiles`

2. Check the status with `git status`.
3. Stage the changes with `git add`.

  Example: `git add vimrc`

4. Commit the changes with `git commit`.
   Write a commit message that describes your changes.
5. Push to remote repository (Github) with `git push`.


### Pull changes from Github ###

1. `cd` to the directory that contains the repository.

  Example: `cd ~/.dotfiles`

2. Pull the changes with `git pull`.


Commands
--------

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
