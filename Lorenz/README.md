# Atractor de Lorenz en Python

Este programa en Python genera una animación del Atractor de Lorenz utilizando la librería ColabTurtlePlus y svgwrite. El código se ejecuta en Colab.

![alt text](https://github.com/Jeidsgn/Dibujos_matematicos/blob/main/Lorenz/files/Animacion_Lorenz.gif)

## Atractor de Lorenz
El Atractor de Lorenz es un sistema dinámico caótico en tres dimensiones que fue estudiado por el meteorólogo Edward Lorenz en la década de 1960. El atractor es conocido por su forma característica de mariposa, y es un ejemplo clásico de un sistema dinámico no lineal.

## Cómo funciona el programa
El programa utiliza las ecuaciones diferenciales del Atractor de Lorenz para calcular las nuevas posiciones x, y, z en cada iteración del bucle while. También dibuja una línea en un archivo SVG para representar el camino que sigue el sistema en el espacio tridimensional.

El programa utiliza la librería ColabTurtlePlus para mover la tortuga a la nueva posición y svgwrite para dibujar la línea en el archivo SVG.

## Cómo ejecutar el programa
Descarga el código y abrelo en Colab.
Ejecuta todas las celdas del cuaderno.
Después de ejecutar el programa, encontrarás un archivo SVG llamado Lorenz.svg en tu directorio de trabajo.

## Créditos
Parte del código fue obtenido del blog de Geoff Boeing [Animating the Lorenz Attractor with Python](https://pages.github.com/)
