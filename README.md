# Plantilla-latex

Una plantilla de latex sencilla con comentarios.

La plantilla la voy actualizando conforme voy escribiendo más documentos con latex. 

## Requisitos

Esta plantilla requiere configurar *minted*, un paquete para mostrar código en latex de forma sencilla y bonita.
La guía de *minted* puedes encontrarla [aquí](http://ctan.mirrorcatalogs.com/macros/latex/contrib/minted/minted.pdf)

## Compilación

Al utilizar el paquete *minted*, al compilar hay que pasarle la opción *--shell-escape*.

Pero para no tener que estar compilando cada vez que queramos visualizar el fichero (por ejemplo tras un cambio), existe una utilidad que actualiza automáticamente el fichero pdf cuando detecta un cambio en el fichero latex

    latexmk
  
Yo uso el siguiente comando:

    latexmk -shel--escape -pdf -pvc plantilla.tex
    

