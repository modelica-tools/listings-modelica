# listings-modelica

This project provides syntax highlighting definitions of the [Modelica language](https://modelica.org) for the LaTeX [listings package](http://www.ctan.org/tex-archive/macros/latex/contrib/listings/).

## Usage

Copy or link the file `modelica-listings.cfg` into your LaTeX project and
include it in your main project file.

E.g.:

    \usepackage{listings}
    \input{listings-modelica.cfg}

The modelica `modelica-listings.cfg` file also provides to new commands,
`\code` and `\modelica`, in order to inline code examples without and with
Modelica syntax highlighting, repsectively.

By default no background colour is set for the listing.
But the appearance can be modified for example by doing:

    \usepackage{listings}
    \input{listings-modelica.cfg}
    \lstset{language = modelica,
            basicstyle=\fontsize{9pt}{10.5pt}\ttfamily,
            backgroundcolor = \color{green}}

## License

&copy; Copyright 2014 Martin Sj&ouml;lund, Dietmar Winkler

This work may be distributed and/or modified under the
conditions of the [LaTeX Project Public License](LICENSE), either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

## Contributions

See [list of contributors](../../graphs/contributors).

[Issues](../../issues) or [pull request](../../pulls) are always welcome.
