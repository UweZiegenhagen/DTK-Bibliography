# dtk-bibliography

This package contains the bibliography for "Die TeXnische Komödie", the
journal of the German-speaking user group.

It is updated on a quarterly basis.

For comments and suggestions please contact the maintainer: Uwe Ziegenhagen, ziegenhagen@gmail.com

# How to produce dtk-bibliography.pdf

Run dtk-bibliography.tex through Arara or run the following commands manually:

* pdflatex dtk-bibliography.tex
* biber dtk-bibliography
* pdflatex dtk-bibliography.tex
* pdflatex dtk-bibliography.tex

Note that dtk-authoryear.bbx and dtk-authoryear.dbx must be in the same directory
respectively the texmf tree.

# License 

This material is subject to the LaTeX Project Public License 1.3c.

# Last update

DTK 02/2020