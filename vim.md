Vim
==========================

I use vim as my primary editor. Reasons for this include:

* Vim provides a standard interface that can be used for all of the
  environments I tend to work with daily. These environments include:
  
  * c++
  * python
  * ruby
  * javascript
  * sql
  * xml
  * html
  * markdown
  * latex
  * restructured text

* Vim plugins are complex to setup, but once setup, provide a very powerful
  editing experience.
* Many of the languages I work with are highly dynamic. As such, code
  inspection tools tend to work little better than tagging solutions.
* I prefer the vim keyboard navigation and while some keyboard navigation
  plugins can be quite good, you can still have a jarring experience when they
  only implement 80% of the keystrokes you are used to.
 
Vim vs other editors
--------------------------

I personally prefer vim over these other editors for the following reasons

* [Emacs](http://www.gnu.org/software/emacs/)

  * I find the vim keyboard sequences easier to type
  * I find vimscript easier to understand than lisp
  * I find vim online resources easier to digest

* [Notepad++](http://notepad-plus-plus.org/) 

  * Uses less efficient keystroke sequences
  * Fewer plugins
  * Only cosmetically simpler to learn. 

* [Jetbrains](https://www.jetbrains.com/) ides such as [RubyMine](https://www.jetbrains.com/ruby/), [PyCharm](https://www.jetbrains.com/pycharm/), [CLion](https://www.jetbrains.com/clion), etc

  * The ides are very powerful, but it license costs to cover the range of
    editors I need are non-trivial
  * Jarring experience to flip between these editors and vim for file types
    that are not supported
  * Lack plugins or functionality for certain types of actions I use a great
    deal such as comments and macros

* [Visual Studio](http://www.visualstudio.com/)

  * Common operations like opening files are very slow. I hope jetbrains
    resharper plugins for c++ will help here, but time will tell. 
  * Hard to get good support for vim keystokes
  * Snippets are not as powerful as ultisnips
  * Does not support all of the file types I tend to have to use each day so
    switching to vim can be jarring.

* [Sublime Text](http://www.sublimetext.com/) 

  * Similar arguments as notepad++. Just has hard to learn if you use it with a
    keyboard first mentality and lacking vims ability to be customized.

Learning Vim
--------------------------

Vim can be challenging to initially learn since its so different from what many
people are accustomed.

I would argue that learning vim is similar to learning any application who's
primary input is through the keyboard. You always have the challenge of
allowing people to control the app while also inputing content using a standard
set of keys. This naturally leads to a need to develop a certain degree of
muscle memory for the keyboard command sequences. 

Please see
[learning vim](https://github.com/ianreay/doc/blob/master/vim-learning.md) for
info about
how to learn vim.

Plugins
--------------------------

Some people prefer vim in its pure state with no plugins and no customizations
to the environment. I believe this can be beneficial when you are a system
administrator and require a custom editing experience across large numbers of
systems where there are strict restrictions on what can be installed.

I work as a software developer though and I spend 95% of my time using vim from
two systems that I have full access to. Being as efficient as I can be in that
environment is paramount. When I'm on other systems, I tend to be doing more
minor tasks like checking logs and editing configurations which rarely requires
the advanced plugins that I find so valuable when doing software development.

Please see my [plugin
list](https://github.com/ianreay/doc/blob/master/vim-plugins.md) for more info
about the plugins I use.

