# Plantilla LaTeX de Tesis

Este proyecto LaTeX puede tomarse como plantilla de *presentación* para conferencias, congresos, seminarios, entre otros.


## Dependencias

Se requiere de una distribución de LaTeX (se recomienda [MikTeX](https://miktex.org/)), el software de gestión de referencias BibTeX y una aplicación para edición (se recomienda [TeXstudio](https://www.texstudio.org/)). 

Además, hay gráficos opcionales que se generan con Tikz.


## Estructura

La estructura de ficheros y directorios es la siguiente:

```
PlantillaBeamer/
├── bibliografia.bib
├── Charla_GEM_main.aux
├── Charla_GEM_main.bbl
├── Charla_GEM_main.blg
├── Charla_GEM_main.log
├── Charla_GEM_main.nav
├── Charla_GEM_main.out
├── Charla_GEM_main.pdf
├── Charla_GEM_main.snm
├── Charla_GEM_main.synctex.gz
├── Charla_GEM_main.tex
├── Charla_GEM_main.toc
├── choice_biblio.bib~
├── gem_3.bbl~
├── IMGS
│   ├── barbero.jpg
│   ├── cantor.jpg
│   ├── choice.png
│   ├── cohen.jpg
│   ├── godel.png
│   ├── hilbert-hotel-L.jpg
│   ├── hilbert-hotel-R.jpg
│   ├── rubik.jpg
│   ├── tarski.jpg
│   └── zermelo.jpg
└── SECTIONS
    ├── seccion1.tex
    ├── seccion2.tex
    └── seccion3.tex
```


## Uso

La compilación se realiza con el fichero control `Charla_GEM_main.tex`.

La clase de documento LaTeX (documentclass) es una modificación de la clase beamer.

El resultado de la compilación es un archivo PDF llamado [`Charla_GEM_main.pdf`](https://github.com/DanielCamarena/PlantillaCharla/blob/main/Charla_GEM_main.pdf).


## Recomendaciones

- Usar Detexify/Mathpix para facilitar el manejo de formulas matemáticas.
- Usar aplicaciones online para facilitar el manejo de tablas.
- Usar Mendeley/JabRef para gestionar las referencias bibliograficas.
- Usar Illustrator/Autocad para generar imágenes vectoriales.
- Usar Python/R/Matlab para obtener gráficos vectoriales.


## Contacto

vcamarenap@uni.pe
