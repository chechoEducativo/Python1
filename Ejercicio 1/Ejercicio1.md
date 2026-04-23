# Ejercicio 1: Pre-Requisitos de desarrollo

Este primer ejercicio consiste en instalar todas las herramientas necesarias para poder desarrollar los retos siguientes.

## 1. Python

Dirigete a la pagina de descargas oficial de [python](https://www.python.org/) y descarga la ultima versión disponible

## 2. IDE

Cualquier IDE que soporte python es util para desarrollar en este lenguaje, afortunadamente este lenguaje es lo  suficientemente flexible
para trabajar en casi cualquier entorno, recomiendo [PyCharm (preferible)](https://www.jetbrains.com/pycharm/) o [VSCode](https://code.visualstudio.com/)

## 3. Venv

Python tiene un sistema flexible para aislar los contextos (o proyectos) en los que se usan librerías y se ejecuta codigo, cada uno de estos proyectos
se encapsula en "Entornos Virtuales" o "Virtual Environments", los cuales llevan un registro de la versión de python, las librerias, las configuraciones de ejecución, etc. Para cada proyecto en especifico, aislando de esta manera la ejecución de codigo en distintos proyectos

Una vez instalada cualquier versión moderna de python, se puede crear un entorno virtual para el proyecto en el que se quiere trabajar de la siguiente manera:

``` bash
cd ruta/del/proyecto/de/python
python -m venv venv
```
esto creará una carpeta con el nombre "venv" en la que se configurará todo lo necesario para el entorno virtual (esta carpeta debe ser ignoarada por git)

una vez creado el entorno virtual, se deberá activar de la siguiente manera

``` bash
.\venv\Scripts\activate
```

de esta manera el entorno ha sido activado y cualquier comando de python que suceda esta llamada será ejecutado a través del entorno virtual
