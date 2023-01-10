# Álgebra Lineal con `R` 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pedritomelenas/R-algebra-lineal/HEAD)

Este repositorio no pretende ser un manual de programación de `R`. Está orientado a introducir al alumno al lenguage `R` mediante la resolución de algunos problemas de Álgebra Lineal. Para ello se han creado una serie de blocs de `jupyter` que pretenden mostrar varios apectos y librerías de `R` que pueden ser utilizados para la resolución de problemas de Álgebra Lineal. 

El primer documento por el que se debería empezar es el titulado [R-matrices.ipynb](https://github.com/pedritomelenas/R-algebra-lineal/blob/main/R-matrices.ipynb), que pretende dar las nociones básicas para definir vectores y matrices en `R`, así como las operaciones elementales con vectores y matrices.  

En el bloc [R-programacion-elemental.ipynb](https://github.com/pedritomelenas/R-algebra-lineal/blob/main/R-programacion-elemental.ipynb) se muestran los primeros pasos para usar condicionales, bucles y definir nuestras propias funciones en `R`. Anque no es estrictamente necesario para la el seguimiento del resto de los documentos de este repositorio, se recomienda su lectura.

Los blocs con prefijo ALME contienen una serie de ejercicios propuestos por L. Merino y E. Santos en su [página de resolución de ejercicios tipo](https://www.ugr.es/~lmerino/ALME.html) de su libro [Álgebra lineal con métodos elementales](https://www.amazon.es/%C3%81lgebra-lineal-m%C3%A9todos-elementales-GONZALEZ/dp/8497324811). Para la resolución de estos problemas se utilizarán las librerías `pracma`, `fractional`, `matlib`, `Ryacas`, entre otras. Los ejercicios están divididos en cuatro bloques.

- [ALME-sistemas-matrices-determinantes.ipynb](https://github.com/pedritomelenas/R-algebra-lineal/blob/main/ALME-sistemas-matrices-determinantes.ipynb) contiene  Estos ejercicios son relativos a transformaciones elementales por filas y columnas de una matriz, determinantes y sistemas de ecuaciones.

- [ALME-espacios-vectoriales.ipynb](https://github.com/pedritomelenas/R-algebra-lineal/blob/main/ALME-espacios-vectoriales.ipynb) contiene ejercicios relativos a dependencia lineal, subespacios, suma, intersección y suma directa de subespacios, ecuaciones cartesianas y paramétricas, cambio de base, matriz de Gram, ortogonalización y proyecciones.
