<p align="center">
  <br/>
  <img src=images/marcauma-total-2.jpg alt="UMA">
  <br/>
</p>

# TFM-UMA

Plantilla para la elaboración del Trabajo de Fin de Máster (TFM) de la Universidad de Málaga, siguiendo la [Guía de Elaboración Memoria TFM](https://www.uma.es/etsi-informatica/navegador_de_ficheros/docs/descargar/TFM/Guia%20Elaboracion%20Memoria%20TFM.pdf) a fecha de **junio de 2023**.
Cabe mencionar que esta plantilla es más orientativa que obligatoria, ya que según la propia Guía:
> No supone necesariamente una restricción en el formato y organización de la memoria, sino que sólo establece algunos contenidos mínimos que deben tratarse.  La organización final de la memoria, así como el orden de las secciones queda a criterio del autor. 

Puedes ver un ejemplo de memoria generada en el fichero [main.pdf](main.pdf).

## Estructura del proyecto

El método más sencillo para usar esta plantilla es crear un nuevo proyecto en [Overleaf](https://www.overleaf.com) e importar todo el contenido de este repositorio en formato ZIP. Esto facilita la escritura del TFM (ya que no es necesario instalar LaTeX) tanto para el alumno como los tutores, ya que permite la edición colaborativa. 

El alumno solo debe modificar el fichero `datos.tex` e introducir la información que se solicita. A continuación, podrá completar la memoria modificando los ficheros que se encuentran en la carpeta [pages](pages).

> La primera página del documento se corresponde con la *etiqueta*, que **NO** debe incluirse en la memoria. Irá pegada sobre la cubierta facilitada por el centro.

> La plantilla fuerza que las páginas de agradecimientos, el resumen, los capítulos del cuerpo y los anexos empiecen en páginas impares siguiendo el formato de un libro.

> Los capítulos están separados en diferentes ficheros. Si se quiere añadir o eliminar algún capítulo, debe crear o suprimir el fichero del capítulo en la carpeta [pages](pages) y modificar el fichero `chapters.tex`.

## Bibliografía

Esta plantilla hace uso de `biblatex` para el manejo de la bibliografía. Para incluir alguna referencia bibliográfica, modifique el archivo `references.bib`.

> Puede leer más en [Bibliography Management](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management#biblatex).

## Agradecimientos

Esta plantilla está basada en la realizada por benhid, que puedes consultar [aquí](https://github.com/benhid/TFG-UMA). 