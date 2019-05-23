# ConectaR2019: Taller de análisis de textos usando R


## Descripción
Este taller tiene por objetivo introducir a sus participantes en algunas estrategias de procesamiento y visualización de textos usando R. Abordaremos aspectos propios del flujo de trabajo de este tipo de datos, como la importación de archivos en distinto formato, la construcción de un corpus, la importancia de la visualización para la identificación de patrones, la interpretación de resultados  entre otros. Además, discutiremos la pertinencia de algunas estrategias de análisis dependiendo de la pregunta que se quiere responder, así como de la naturaleza de los datos de los que se dispone.
El taller solo requiere un conocimiento básico de R: saber cómo instalar un paquete y cómo ejecutar el código.

## Paquetes a utilizar
Para el taller es necesario tener los siguentes paquetes instalados.

### Procesamiento de datos

```r
install.packages("tokenizers")
install.packages("tidyverse")
install.packages("glue")
```

### Importación de textos a R

```r
install.packages("pdftools")
install.packages("readtext")
install.packages("rvest")
```

### Reconocimiento óptico de caracteres

```r
install.packages("tesseract")
```
Usuarios de Linux, revisar [el siguiente enlace para la instalación](https://github.com/ropensci/tesseract)

### Análisis de textos

```r
install.packages("quanteda")
install.packages("udpipe")
install.packages("syuzhet")
install.packages("tidytext")
```

## Datos
Los datos que usaremos en el taller están contenidos en la carpeta `ConectaR_textmining` en este mismo repositorio. Una versión de la misma se encuentra en este [enlace de Dropbox](https://www.dropbox.com/sh/x1u67e4cqi4zktz/AAAlpd7FIQshAlNhilVsN0uPa?dl=0).

## Código en vivo
Durante el taller, todo el código que vaya escribiendo irá apareciendo en [este siguiente enlace](https://www.dropbox.com/s/d3t0jlgpbtddnug/script_taller.R?dl=0).

## Referencias
[pŕoximamente]
