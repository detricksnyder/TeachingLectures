TeachingLectures
================

These are the lecture slides and lecture notes for courses that I have taught.
Each course is in a directory, then each lecture is in a subdirectory of that folder.

Format
--------
The lectures are written in markdown format  (see <http://en.wikipedia.org/wiki/Markdown>) and then parsed into slides and handouts using pandoc using the following commands:

    pandoc -t beamer lecture.md -V theme:Warsaw -o lecture-slides.pdf
    pandoc lecture.md -o lecture-notes.pdf
