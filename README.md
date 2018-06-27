# RPG LaTeX Template

This is an attempt at a RPG LaTeX template.
The template compiles with xetex and pdflatex.

### Book
Full preview https://github.com/Krozark/RPG-LaTeX-Template/raw/master/sample/book.pdf

![Preview](https://raw.githubusercontent.com/Krozark/RPG-LaTeX-Template/master/sample/book.jpg)

### Cards
![Preview](https://raw.githubusercontent.com/Krozark/RPG-LaTeX-Template/master/sample/cards.png)

### Installation

Just clone the repo. From terminal:

```sh
$ git clone https://github.com/Krozark/RPG-LaTeX-Template.git
$ cd RPG-Latex-Template
$ xelatex book.tex
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

### Todo's

 - Consider implementing more complex tables for monsters, etc.
 - Clean up the table-preset
 - Create more elegant solution for spacing before and after boxes (using \vspace is rather rigid when two boxes follow in a row)
 - Add subtitle option for boxes
 - Sort out box-decals when boxes break column or page
 - Look into adding the ability to add large images to the document. There are some documents made with InDesign out there that accomplish this quite well.


### Credit

 - Background : http://lostandtaken.com/
 - Sword : http://opengameart.org/content/medieval-sword
 - Icons : http://game-icons.net/
 - The fonts in this documents were made by Reddit user /u/Solbera, and are released under the CC-BY-SA 4.0 license.
 - Some decorations (footers, headers, etc.) were ripped and vectorialised from the Player's Handbook and are probably not safe to redistribute as such.
 - The background image is from the Homebrewery, created by Scott Tolksdorf, and is released under the MIT license.

