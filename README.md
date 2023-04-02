# Plantilla LaTeX de Tesis

Este proyecto LaTeX puede tomarse como plantilla de *presentación* para conferencias, congresos, seminarios, entre otros.


## Dependencias

Se requiere de una distribución de LaTeX (se recomienda [MikTeX](https://miktex.org/)), el software de gestión de referencias BibTeX y una aplicación para edición (se recomienda [TeXstudio](https://www.texstudio.org/)). 

Además, hay gráficos opcionales que se generan con Tikz.


## Estructura

La estructura de ficheros y directorios es la siguiente:

```
PlantillaTesis/
├── 0_0_PREAMBULO
│   └── Preambulo.tex
├── 1_1_PROTOCOLAR
│   ├── Agradecimientos.tex
│   ├── Caratula.tex
│   ├── Dedicatoria.tex
│   └── Licencia.tex
│   └── Simbolos.tex
├── 2_CAPITULO1
│   ├── Capitulo1.tex
│   ├── Capitulo2.tex
│   ├── Capitulo3.tex
│   └── Secciones
│   ├── Conclusiones.tex
│   └── Recomendaciones.tex
├── 3_2_BIBLIOGRAFIA
│   ├── Bibliografia.tex
│   └── library.bib
├── 3_3_ANEXOS
│   ├── Anexos.tex
├── E_IMAGENES
│   ├── 1_Protocolar
│   │   └── UNI_LOGO1.pdf
│   ├── 2_Capitulo2
│   ├── 2_Capitulo3
│   ├── 2_Capitulo4
│   └── 3_Anexos
├── T_TABLAS
│   └── 2_Capitulo3
├── .gitignore
├── LICENSE
├── README.md
├── TESIS_UNI_main.pdf
└── TESIS_UNI_main.tex
```


## Uso

La compilación se realiza con el fichero control `TESIS_UNI_main.tex`, previamente debe configurar en su aplicación de edición la compilación con el motor XeLaTeX (el motor PdfLaTeX da error).

La clase de documento LaTeX (documentclass) es una modificación de la clase book, esto corresponde al archivo `TesisUNI.cls` (evite editar dicho archivo).

El esquema de carátula de la tesis queda definida en el fichero `1_0_CARATULA/Caratula.tex` (edite lo menos posible dicho archivo), y puede modificarse los datos de la carátula desde el preámbulo en el fichero `0_0_PREAMBULO/Preambulo.tex`.

El resultado de la compilación es un archivo PDF llamado [`TESIS_UNI_main.pdf`](https://github.com/DanielCamarena/PlantillaTesis/blob/main/TESIS_UNI_main.pdf).


## Recomendaciones

- Usar Detexify/Mathpix para facilitar el manejo de formulas matemáticas.
- Usar aplicaciones online para facilitar el manejo de tablas.
- Usar Mendeley/JabRef para gestionar las referencias bibliograficas.
- Usar Illustrator/Autocad para generar imágenes vectoriales.
- Usar Python/R/Matlab para obtener gráficos vectoriales.


## Contacto

vcamarenap@uni.pe