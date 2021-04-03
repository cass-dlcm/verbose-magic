# Verbose Magic

This is an attempt at a RPG LaTeX template.
The template compiles with xetex and pdflatex.

### Installation

Just clone the repo. From terminal:

```sh
$ git clone git@github.com/cass-dlcm/verbose-magic.git
$ cd RPG-Latex-Template
$ xelatex book.tex
```

If you don't have LaTeX installed, the following should help you out:
#### Ubuntu
```sh
sudo apt-get install texlive-full
```
#### Arch
```sh
sudo pacman -S texlive-bin texlive-core texlive-latexextra
```
It's a bit unclear exactly what subset of features this module needs. As a general rule, we'd recommend installing one of larger ones.

### Todo's

 - Consider implementing more complex tables for monsters, etc.
 - Clean up the table-preset
 - Create more elegant solution for spacing before and after boxes (using \vspace is rather rigid when two boxes follow in a row)
 - Add subtitle option for boxes
 - Sort out box-decals when boxes break column or page
 - Look into adding the ability to add large images to the document. There are some documents made with InDesign out there that accomplish this quite well.


### Credit

 - Original template by Krozarth, located at https://github.com/Krozark/RPG-LaTeX-Template.git
 - The fonts in this documents were made by Reddit user /u/Solbera, and are released under the CC-BY-SA 4.0 license.
 

