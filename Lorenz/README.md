# Atractor de Lorenz en Python

Este código dibuja el atractor de Lorenz, que es un sistema dinámico caótico no lineal, mediante el uso de la tortuga de Python y la librería svgwrite. El resultado es un archivo SVG que muestra la trayectoria bidimensional en el espacio tridimensional del atractor de Lorenz.

Este código está hecho para ser utilizado en Google Colab

![alt text](https://github.com/Jeidsgn/Dibujos_matematicos/blob/main/Lorenz/files/Animacion_Lorenz.gif)

## Atractor de Lorenz
El Atractor de Lorenz es un sistema dinámico caótico en tres dimensiones que fue estudiado por el meteorólogo Edward Lorenz en la década de 1960. El atractor es conocido por su forma característica de mariposa, y es un ejemplo clásico de un sistema dinámico no lineal.

## Cómo funciona el programa
El programa utiliza las ecuaciones diferenciales del Atractor de Lorenz para calcular las nuevas posiciones x, y, z en cada iteración del bucle while. 
El código dibujará el atractor de Lorenz y creará un archivo SVG llamado "Lorenz.svg" en el directorio actual.
El archivo SVG se visualizará en la salida de la celda, para representar el camino que sigue el sistema en el espacio tridimensional.

El programa utiliza la librería ColabTurtlePlus para mover la tortuga a la nueva posición y svgwrite para dibujar la línea en el archivo SVG.

## Cómo ejecutar el programa
Descarga el código y abrelo en Colab.
Ejecuta todas las celdas del cuaderno.
Después de ejecutar el programa, encontrarás un archivo SVG llamado Lorenz.svg en tu directorio de trabajo.

## Créditos
Parte del código fue obtenido del blog de Geoff Boeing [Animating the Lorenz Attractor with Python](https://pages.github.com/)

## Licencia
Este código es de dominio público.
