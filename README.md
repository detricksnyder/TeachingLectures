TeachingLectures
================

These are the lecture slides and lecture notes for courses that I have taught.
Each course is in a directory, then each lecture is in a subdirectory of that folder.

Format
--------
The lectures are written in markdown format  (see <http://en.wikipedia.org/wiki/Markdown>) and then parsed into handouts using pandoc using the following commands:

    pandoc lecture-notes.md --biblio references.bib --csl chicago-author-date.csl -o lecture-notes.pdf

Slides can be generated with the following command, though most often the slides are generated with powerpoint to facilitate use of clickers and animation.

    pandoc -t beamer lecture-notes.md -V theme:Warsaw -o lecture-slides.pdf
