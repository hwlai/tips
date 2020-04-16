Vim
===

Use `:help <letter/symbol>` from within Vim to get more information about a
certain motion/operator/text object etc., for example `:help ;` and `help dd`.


Operater
--------

* `ci` - change inner text object + insert mode 
* `ca` - change a text object 
* `di` - delete inner text object 
* `da` - delete a text object 

Text object
-----------
* `{} [] ()`
* `'' ""`
* `w` - word
* `s` - sentence

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

### Other motion ###

* ` `` ` - previously changed line
* `` `. `` - previously changed location


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


Splits
------

* `:sp` - Create a horizontal split
* `:vs` - Create a vertical split
* `:q` - Close split
* `Ctrl-w h` - Navigate to split on the left
* `Ctrl-w j` - Navigate to split below
* `Ctrl-w k` - Navigate to split above
* `Ctrl-w l` - Navigate to split on the right
* `Ctrl-w w` - Navigate to the next split

