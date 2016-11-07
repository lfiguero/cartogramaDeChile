# cartogramaDeChile: Mapa deformado con área proporcional a población

[https://github.com/lfiguero/cartogramaDeChile](https://github.com/lfiguero/cartogramaDeChile)

Este es el segundo proyecto de 525490 (2016-II).

* Fecha de entrega: 06/dic/2016 23:59:59 CLST
* Modo de entrega: Informe (LaTeX) y códigos computacionales mediante un *pull request* a este repositorio.
* Como ahora hay un solo alumno, no es necesario poner archivos en subdirectorio nombrado con apellido.
* Por favor, subir solamente los archivos fuente del informe y los códigos (.tex, .bib, .c, .f90, PDF con imágenes usadas en el informe, datos de entrada, etc.) y no las salidas (PDF de salida, .aux, .log, .o, etc.).
* Lenguajes de programación admisibles:
    + C/C++
    + Fortran
    + Julia
    + Octave (similar a Matlab)
    + Python
    + Scilab (similar a Matlab)
    + Algún otro solamente bajo previa aprobación del profesor

## Descripción del problema

Construya con *cartograma* (inglés: *cartogram*) de Chile usando el método del artículo:

M. T. Gastner & M. E. J. Newman, *Diffusion-based method for producing density-equalizing maps*, PNAS **101**(20):7499–7504, 2004, doi:[10.1073/pnas.0400280101](https://dx.doi.org/10.1073/pnas.0400280101).

Existe una implementación en C en [http://www-personal.umich.edu/~mejn/cart/](http://www-personal.umich.edu/~mejn/cart/).

La densidad poblacional del mapa de Chile inicial debe tener granularidad al menos al nivel de comuna.
