Learning Vim
==========================

Learning vim is not something you do overnight. It takes time to develop the
muscle memory to use vim effectively. The speed improvements and personal
efficiency will be well worth the investment. 

Installation - Windows
--------------------------

Installation - Unix
--------------------------

Gvim UI
--------------------------

The graphical vim (gvim) user interface has many commands that you can use just
like notepad++ and other graphical editors. It can be very tempting to use
these when you are learning vim. I tried doing this when I first started to
learn vim and I believe it was a mistake for me personally. The reasons are:

* Vim is only efficient if you have the muscle memory to use it. Using the
  graphical UI does not develop muscle memory.
* 90% of your editing in vim will only require 20 or so commands. Biting the
  bullet and learning those 20 commands is really the only way to become
  efficient with vim.
* Most vim plugins do not add UI elements that help with their usage. To use
  them effectively, you really need to learn their keyboard helpers.

Using gvim is fine, but I would strongly advise using gvim as if it was the
terminal version of vim with no advanced menu options and have quick reference
sheets for learning the various vim commands.

Practical Vim
--------------------------

Now that you have the basic commands down, its time to start learning more
about vim. By far the best book I have seen on vim is [Practical
Vim](https://pragprog.com/book/dnvim/practical-vim). The author of the book is
great at explaining the reasons why vim is the way it is. Understanding why
things are done the way they are really helps in learning vim.

Week 1: Vim Tutor
--------------------------

On Unix, if Vim has been properly installed, you can start it from the shell:
>
	vimtutor

On MS-Windows you can find it in the Program/Vim menu.  Or execute
vimtutor.bat in the $VIMRUNTIME directory.

This tool gives you a very good initial summary of vims basic commands that include

* Efficiently moving the cursor
* Closing down vim
* Vims modes - insert, command, visual, etc.
* etc

It will take time to learn vim. You will require some quick reference notes to
help you remember the commands. For example:

* [vim cheat sheet](http://www.viemu.com/vi-vim-cheat-sheet.gif) 

I personally don't find these all that useful. I found it personally more
effective to make up small notes of 5 to 10 commands that I try to learn at a
time. Get those committed to muscle memory and then move onto another 5 to 10
commands. Attempting to learn tens or hundreds of commands all at once can be
overwheling and lead to frustration quickly.

First ten commands:

* esc - go to [normal mode](https://pragprog.com/book/dnvim/practical-vim) 
* i - go to [insert mode](https://pragprog.com/book/dnvim/practical-vim) 
* :q - quit vim
* :e file - open file
* :s - save
* h - cursor left
* j - cursor down
* k - cursor up
* l - curosr right
* u - undo

These first 10 commands will help you become about as efficient in vim as you
are with notepad. The next 10 commands will get you to be more powerful than
notepad and on par with other more advanced text editors.

It is critically important that vim users understand the difference between
command mode and insert mode. Vim is unique in that it has different distinct
modes. The best way I have heard the modes explained is if you think of
yourself as an artist. Artists spend most of their time planning out their next
brush stroke and reviewing their masterpiece. This is normal mode. Artists
spend most of their time in normal mode and so should you.

Once an artist has planned out their change, they put brush to canvas. This is
insert mode. You do a few quick brush strokes then you leave insert mode to
plan out your next set of changes.

Once in a while, an artist needs to do something on a block of their
masterpiece. They need to select that block and then do something across the
entire block - ie set it to a uniform background color. This is what visual
mode is useful for.

Artists need to infrequently get more supplies. More paint, different canvas,
etc. This is command mode. You reach out and get something that is unrelated to
the masterpiece you are working on. Command mode allows you to do things like:

* compile your masterpiece
* run a syntax checker
* list content from a file and place it in the current buffer.
* etc...

As a rule, you shoud spend the following percentages of time in the various modes:

* normal - 90% of your time.
* insert - 7% of your time.
* visual - 2% of your time.
* command - 1% of your time.

Next 10 commands:

* w - next word
* b - previous word
* C-u - up half a page
* C-d - up half a page
* y - yank (copy) the current line
* d - delete the current line
* p - paste the current line
* u - undo last change
* /expression - search down for expression in the current file
* ?expression - search up for expression in the current file

These 20 commands should allow you to start being efficient in vim. There are
many more commands to learn, but these will be your primary commands that you
use all the time. 


