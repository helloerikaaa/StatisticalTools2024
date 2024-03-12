# Statistical Tools for Data Analysis
Repositorio de la Materia Statistical Tools for Data Analysis de la Ingeniería en Sistemas Computacionales de UPIIZ-IPN

## Contenido
* Unidad I: [Estadística Descriptiva e Inferencial](https://github.com/helloerikaaa/StatisticalTools2024/tree/main/I)
* Unidad II: Regresión
* Unidad III: Procesos estocásticos aleatorios y series de tiempo
* Unidad IV: Patrones de puntos espaciales

## Pre Requisitos
* Python 3.9+
* Astral UV
* Git
* Jupyter Notebooks

## Clonación del repositorio
Para utilizar este repositorio, es necesario tener el conocimiento básico de Git.

Para comenzar, se debe clonar el repositorio en sus computadoras, este comando se debe ejecutar desde la consola, dentro de la carpeta donde se desea guardar el repo. Por ejemplo, si quieren guardarlo en C:/Documentos, entonces tendrán ubicarse en esa ruta desde la consola.

```bash
git clone https://github.com/helloerikaaa/StatisticalTools2024.git
```
Cada clase el repositorio se va a actualizar con el contenido que se haya visto, para obtener la versión más actualizada, se utiliza el siguiente comando:
```bash
git pull
```

## Dependencias
El repositorio cuenta con un archivo llamado `requirements.txt`, el cual contiene todas las librerías necesarias para ejecutar los Jupyter Notebooks en sus computadoras.


### Ejecución del Ambiente Virtual
Con el objetivo de tener una instalación más limpia y organizada, es necesario crear un ambiente virutal para este proyecto, donde únicamente se instalarán los paquetes requeridos por los Jupyter Notebooks vistos en clase, para crear el ambiente es necesario ejecutar el siguiente comando:
```bash
uv venv .venv-stats
```

### Instalación de Paquetes
Una vez que el ambiente virtual está activado, se puede hacer la instalación de las dependencias con el comando:
```bash
source ./.venv-stats/bin/activate
uv pip install -r requirements.txt
```

## Jupyter Notebooks
Los Jupyter Notebooks son entornos interactivos de computación que permiten combinar código, texto explicativo y visualizaciones en un mismo documento. Para trabajar con ellos hay dos opciones:
1. Ejecutar el ambiente web
JupyterLab es una interfaz de usuario basada en web para la computación interactiva con Jupyter Notebooks, para ejecutar esta aplicación, dentro del ambiente virutal, es necesario correr el siguiente comando:
```bash
jupyter lab
```
2. Ejecutar desde Visual Studio Code
Con VSCode se pueden ejecutar los Jupyter Notebooks de una manera sencilla, lo único que se tiene que instalar es la extensión de Jupyter Lab desde el marketplace de VSCode.

------
## Sobre el uso de información total o parcial:
* Estos documentos fueron originalmente creados por el autor.
* Cualquier uso de estos documentos o sus contenidos están permitidos a través de la licencia provista y sus condiciones.
* Para cualquier aclaración, puedes contactar al autor: https://helloerikaaa.github.io

**Copyright (c) 2024 Erika Sánchez-Femat**