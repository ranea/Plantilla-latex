# Simple latex templates

A latex template for writing articles and presentations.

The templates contains many packages to fulfill the needs of academic articles (graphics, programm code, maths, ...)

## Dependencies

[minted](https://github.com/gpoore/minted)
[metropolis](https://github.com/matze/mtheme)

## Compilation

    latexmk -pdf -quiet -shell-escape article.tex
    
 or
 
    latexmk -pdf -quiet -shell-escape slides.tex
    

