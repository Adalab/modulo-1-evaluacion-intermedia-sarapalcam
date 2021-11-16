# Módulo 1: Ejercicio de evaluación intermedia

En este ejercicio vamos a maquetar una versión simplificada de la Home de la página web de Adalab.

## Elementos

La web simplificada que hemos preparado, consta de estos elementos:

1. Una cabecera fija, que ocupa todo el ancho de la pantalla y que contiene:
   - El logo de Adalab con un enlace a la home.
   - Un menú de opciones en línea.
2. Hay una sección principal que tiene un color de fondo y un título que dice "Creando Diversidad Digital". Este texto tiene que estar centrado tanto vertical como horizontalmente en toda la ventana
   de la página.

## Información de estilo

También os damos información de estilo:

- La tipografía usada es Rubik y el html para añadirlo desde Google Fonts es:

  `<link rel="preconnect" href="https://fonts.gstatic.com"><link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap" rel="stylesheet">`

  Se usa así:

  `font-family: 'Rubik', sans-serif;`

- La paleta de colores usados son:

  - `#4a4a4a` (Texto del menú)
  - `#3CDBC0` (Color de fondo de la página)
  - `#FFFFFF` (Color de texto de "Creando diversidad digital")

Para obtener el logo de Adalab entrad [en este enlace](https://github.com/Adalab/resources/blob/master/images/adalab-logo-155x61.png) y dadle al botón de descargar.

La web realizada tiene que ser responsive, es decir, debe funcionar correctamente para los siguientes tamaños:

### Móvil

- Por defecto
  - El logo tiene un tamaño de 155px de ancho.
  - El menú de la cabecera se coloca bajo el logo.
  - El texto de las opciones del menú tiene un tamaño de 16px.
  - El texto del título "Creando Diversidad Digital" tiene un tamaño de 30px

### Tablet y desktop

- A partir de 768px
  - El menú de la cabecera se coloca a la derecha.
  - El texto de las opciones del menú tiene un tamaño de 16px.
  - El texto del título "Creando Diversidad Digital" tiene un tamaño de 40px.
