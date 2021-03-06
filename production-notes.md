---
layout: book-Getting-Hired
title: Production Notes
prev: '<a href="licence.html">Prev: Licence</a>'
next: '<a href="index.html">Back to: Getting Hired</a>'
---
# Production Notes

If you're curious about the technology and process used to create this book, I hope the following points go someway towards answering your questions.

## Writing

This book was written in [Markdown](http://daringfireball.net/projects/markdown/) notation, using the [Sublime Text 2](http://sublimetext.com) text editor.  Markdown is a very light-weight notation, allowing me to focus on the content of the book without being distracted by presentation issues at the writing stage.

The Markdown sources for this book are hosted on [GitHub](http://github.com) at [github.com/stuartherbert/getting-hired/](https://github.com/stuartherbert/getting-hired/).  The _toc.json_ file contains all of the chapters in the right order; the CLI PHP script _tools/update-nav.php_ is used to re-generate the HTML version's navigation sidebar when necessary.  You're most welcome to send in pull requests to help me improve the book for future editions.

[Jekyll](https://github.com/mojombo/jekyll) was used to convert the Markdown sources into [the HTML version of the book](http://books.stuartherbert.com/getting-hired/).  You can run Jekyll locally on your laptop to proof your changes as you make them.

[Twitter's Bootstrap CSS framework](http://twitter.github.com/bootstrap/) was used as the basis for the HTML version's look and feel.

## Publishing

The final [HTML version of the book](http://books.stuartherbert.com/getting-hired/) is published online via [GitHub Pages](http://pages.github.com/), with the conversion to HTML once again handled by [Jekyll](https://github.com/mojombo/jekyll).

The Markdown sources were converted into an intermediate [LibreOffice](http://www.libreoffice.org/) document using [pandoc](http://johnmacfarlane.net/pandoc/).  This intermediate file was then used to create the PDF, Kindle and ePub editions that you can download from the website.

The Kindle edition was created from the LibreOffice document, using [calibre](http://calibre-ebook.com).  The formatting was controlled by applying a pre-prepared stylesheet to the LibreOffice-format document before exporting to HTML format.  Proofing was done using the Kindle app on the iPad and a physical Kindle Paperwhite device.

The ePub edition was created from the LibreOffice document using [calibre](http://calibre-ebook.com), using the same formatting stylesheet developed for the Kindle edition.  Proofing was done using iBooks preview mode on the iPad.

The PDF edition was created by applying a different pre-prepared stylesheet to the LibreOffice-format document, and then using LibreOffice's "Save As PDF" option.  There are two PDF editions, one sized for British A4 paper, and the other for US letter paper.