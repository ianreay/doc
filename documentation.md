Documentation
=========================

I use a number of different types of documentation systems.

* [Markdown](https://github.com/ianreay/doc/blob/master/documentation.md#Markdown) - personal docs
* [Latex](https://github.com/ianreay/doc/blob/master/documentation.md#Latex) - work docs
* [Sphinx](https://github.com/ianreay/doc/blob/master/documenation.md#Sphinx) with restructured text - python docs

Writing in all of these different formats can be a challenge. Using code snippets can really help in ensuring easy to type and consistently correct docs.

Markdown
-------------------------

I use markdown for any public facing content I generate. This is mostly because it can be hosted in github and is easily available and maintained.

[Markdown Syntax](http://daringfireball.net/projects/markdown/syntax)

Latex
--------------------------

[Latex](http://www.latex-project.org/) is used for customer facing
documentation since it allows for large ecosystems to be built around it that
can remove out many repetitive tasks. 

Pros:

* Its hugely extensible.
* Its a defacto standard that all doc tools tend to have a conversion from and to.
* It generates pdf based documentation very well. 

Cons:

* Its complex to setup.
* Requires compilation phases.
* Broken compiles can be difficult to troubleshoot.
* Its [syntax](http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/) is complex and has a high degree of markup that can make source code of docs difficult to read.

I primarily use the [MiKTEX](http://miktex.org/) latex compiler.

Sphinx
--------------------------

[Sphinx](http://sphinx-doc.org/) is the defacto documentation system for python and I use python a great deal at work.

We use [Restructured Text](http://sphinx-doc.org/rest.html) when using sphinx.

Snippets
-------------------------

Each documentation system has different markup to express common concepts.
Remembering all of this can be quite difficult since some documentation systems
such as latex can be very markup heavy. For this reason, I use
[snippets](http://en.wikipedia.org/wiki/Snippet_%28programming%29) to create
common keystroke sequences that allow me to write documents far more
efficiently and accuratly.

* page - create a new page
* s - create a new section
* ss - create a new sub section
* sss - create a new sub sub section
* il - internal link
* el - external link
* ls - list start
* le - list entry

I use [ultisnips](https://github.com/SirVer/ultisnips) and the [vim](http://www.vim.org/) text editor to write docs with snippets

Quick links:

* [Personal vim setup](https://github.com/ianreay/dotfiles)
* [Personal snippet repository](https://github.com/ianreay/ultisnips)

Screencasts
--------------------------

For some great screencasts about how to use ultisnips with vim see:

* [Meet ultisnips](http://vimcasts.org/episodes/meet-ultisnips/)
* [Using python interpolation in ultisnips](http://vimcasts.org/episodes/ultisnips-python-interpolation/)
* [Using selected text in Ultisnip snippets](http://vimcasts.org/episodes/ultisnips-visual-placeholder/)

