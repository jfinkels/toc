Theory of Computation: An Introduction
======================================

This file was last updated on 7 January 2014.

Downloading
-----------

This book can be found at https://github.com/jfinkels/toc.

To download the LaTeX source code of the book using [Git][1], run

    git clone git@github.com:jfinkels/toc.git

[1]: http://git-scm.com

Compilation dependencies
------------------------

Besides `pdflatex`, the following LaTeX packages are required to compile this
document:

* `graphicx`
* `hyperref`
* `lipsum`
* `listings`

On Ubuntu 13.10, the necessary system packages which contain these LaTeX
packages are:

* `texlive-latex-base`
* `texlive-latex-extra`
* `texlive-latex-recommended`

To install them, run

    sudo apt-get install texlive-latex-base texlive-latex-extra \
      texlive-latex-recommended

Compiling
---------

To compile the document, run

    pdflatex toc
    bibtex toc
    pdflatex toc
    pdflatex toc

The output is `toc.pdf`, and can be viewed with any PDF reader.

Copyright
---------

Copyright 2014 Jeffrey Finkelstein.

Both the LaTeX markup and the compiled book are licensed under the Creative
Commons Attribution-ShareAlike 4.0 International License. To view a copy of
this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a
letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View,
California, 94041, USA. A copy of the license is also available in the file
`LICENSE` in this directory.

Contact
-------

Jeffrey Finkelstein <jeffrey.finkelstein@gmail.com>
