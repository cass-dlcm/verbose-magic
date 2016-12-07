# RPG LaTeX Template

This is an attempt at a RPG LaTeX template.
The template compiles with pdflatex.

### Book
![Preview](https://raw.githubusercontent.com/Krozark/RPG-LaTeX-Template/master/sample/book.jpg)

### Cards
![Preview](https://raw.githubusercontent.com/Krozark/RPG-LaTeX-Template/master/sample/cards.png)

### Installation

Just clone the repo. From terminal:

```sh
$ git clone https://github.com/Krozark/RPG-LaTeX-Template.git
$ cd RPG-Latex-Template
$ pdflatex book.tex
$ pdflatex cards.tex
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

### Package Options
- bg-letter: Loads a letter-sized background-image
- bg-a4: Loads an A4-sized background-image
- bg-print: Loads a printer-friendly background-image (only decal at the bottom)
- bg-full: Loads the full background-image

Per default "bg-letter" and "bg-full" are loaded.

### Todo's

 - Consider implementing more complex tables for monsters, etc.
 - Clean up the table-preset
 - Create more elegant solution for spacing before and after boxes (using \vspace is rather rigid when two boxes follow in a row)
 - Add subtitle option for boxes
 - Sort out box-decals when boxes break column or page
 - Look into adding the ability to add large images to the document. There are some documents made with InDesign out there that accomplish this quite well.


### Image Credit

 - Background : http://lostandtaken.com/
 - Sword : http://opengameart.org/content/medieval-sword

