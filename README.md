TeachingLectures
================

These are the lecture slides and lecture notes for courses that I have taught.
Each course is in a directory, then each lecture is in a subdirectory of that folder.

Versioning
----------

The versioning is based on years of teaching (not years teaching that course).  So release 1.0.0 is the first years lectures delivered as they are prepared.  
Post-lecture updates will be in the second digit until the lecture is delivered again.
New lectures will be developed in a new branch and merged in to the main release once that lecture is delivered.

Format
--------
The lectures are written in markdown format  (see <http://en.wikipedia.org/wiki/Markdown>) and then parsed into handouts using pandoc using the following commands:

    pandoc lecture-notes.md --biblio references.bib --csl chicago-author-date.csl -o lecture-notes.pdf

Slides can be generated with the following command, though most often the slides are generated with powerpoint to facilitate use of clickers and animation.

    pandoc -t beamer lecture-notes.md -V theme:Warsaw -o lecture-slides.pdf
