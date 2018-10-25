EmilyCurtinResume
=================

LaTex files for my resume.

To compile, `git clone` this repo, then:

```
$ latex resume.tex
```

This will produce a .dvi file. On OSX with BasicMacTex installed I can open this DVI in TexWorks which will automatically create a .pdf of the same name in the same file.

Alternately, if you `brew install mactex` (and then close your terminal and open a new one because of a bug with the binary links)
you'll have `pdflatex` installed so you can just

```
$ pdflatex resume.tex
$ open resume.pdf
```
