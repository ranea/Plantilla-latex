# Simple latex templates

Two latex templates for writing articles and presentations.

The templates contain many packages to fulfill the needs of academic articles/presentations (graphics, programm code, maths, ...)

## Dependencies

[minted](https://github.com/gpoore/minted)
[metropolis](https://github.com/matze/mtheme)

## Compilation

    latexmk -pdf -quiet -shell-escape article.tex
    
 or
 
    latexmk -pdf -quiet -shell-escape slides.tex
    

