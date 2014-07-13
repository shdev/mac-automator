# Mac-Automator

## Overview

In this repository you find some more or less useful automator workflows/ apps for your daily life.
Currently they run under OS X 10.9.

## diff-pdf

If you need to compare to PDFs you can do it for free with the command line tool `diff-pdf`. It gives you a comparison of each page with highlighting the differences.

Install it with:

`brew install diff-pdf` 

After that you can use it with:

`diff-pdf --view file1.pdf file2.pdf`

But for people which fear the command line is the automator app `diff-pdf.app`

It asks for the first PDF file, and the second, too and opens the diff-pdf view.

As dependency it needs the `diff-pdf` executable under `/usr/local/bin/diff-pdf`.

As a use case it's good to compare a PDF made by Indesign with and without converted text to path. There is a nasty "feature" which do not convert numbering in text areas. These have to be converted before in text and then you can convert the text in pathes.
