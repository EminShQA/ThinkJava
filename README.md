# ThinkJava
LaTeX source and code examples for Think Java, 6th edition.
Copyright (C) 2016 Allen Downey and Chris Mayfield.

**NOTE: This version of the book is a work in progress and won't be completed
until February 2016.**

Permission is granted to copy, distribute, transmit, and adapt this work under
the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License:
http://creativecommons.org/licenses/by-nc-sa/3.0/

The original form of this book is the LaTeX source code available from
http://thinkjava.org and https://github.com/AllenDowney/ThinkJava.

The illustrations were drawn using xfig (http://www.xfig.org/) and dia
(https://wiki.gnome.org/Apps/Dia/). These tools are free and open-source.

Compiling the LaTeX source has the effect of generating a device-independent
representation of the book, which can be converted to other formats and printed.

To compile the PDF version from source:

    pdflatex thinkjava
    makeindex thinkjava
    pdflatex thinkjava
    pdflatex thinkjava

The source code includes a Makefile that automates this process.
You might have to install texlive-latex-extra (in Ubuntu).
