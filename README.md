# README

This summary was written for Students of the Vienna University of Technology, which take the Machine Learning course. 
The summary should explain most of the basic concepts in depth, the advanced topics are also handled but not as in depth as the basic subjects.

## Please contribute

In an effort to increase the quality of the summary, please add sections/informations/links/etc. you find worthy for this summary. 
For this you can either fork this repository, add the stuff you want to add and then create a pull request (high probability that your changes will get into the summary),
or create an issue (low to medium probability that your remarks will be added to the summary).

If you contribute, please only add necessary files (like images, the changed `.tex` file), but no `.aux`, `.log`, etc. files, thanks.

## Why LaTeX?

Because git works pretty good with LaTeX.

## How can I build the PDF on my own PC?

In the repo a makefile is provided, which specifies the commands necessary to generate the PDF. In general you need two things:

1. A working LaTeX installation
2. Something to build the tex file, so either
    1. an installation of the `make` tool for building programs and then executing `$ make` ([Linux](https://askubuntu.com/questions/161104/how-do-i-install-make), [Windows](https://stackoverflow.com/questions/32127524/how-to-install-and-use-make-in-windows), [Mac](https://stackoverflow.com/questions/10265742/how-to-install-make-and-gcc-on-a-mac))
    2. using a LaTeX editor of your choice and import all the files - it should work then if you use the sequence of programs: `pdflatex` - `biber` - `pdflatex` - `pdflatex`
    
## Figures

All figures were drawn by myself with the Draw.Io / diagrams.net (see [diagrams.net](https://app.diagrams.net/)) tool which can also be downloaded. One can import the file `figures.drawio` in the folder `ìmgs` to add figures.

If one wants to add new figures, please be sure that you actually can share them with other people legally or draw them yourself :-)
