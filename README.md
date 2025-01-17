# Sobre el nuevo estándar de encapsulado de clave (KEM) post–cuántico

 ![image](https://github.com/user-attachments/assets/65c9aa92-a7f1-4685-9d1e-272ca69c054c)

Realizado por: <br>
Gabriel Vacaro Goytia (gabvacgoy@alum.us.es) <br>
Ignacio Warleta Murcia (ignwarmur@alum.us.es) <br>


En este repositorio se encuentran todos los notebooks que se hacen referencia en el proyecto. En los cuales se han desarrollado tanto herramientas para trabajar con las primitivas matemáticas como implementaciones de problemas más complejos. Todo explicado desde un punto de vista didáctico, con el objetivo de un acercamiento más cercano a la materia.

## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción del Proyecto

Este repositorio contienen los anexos realizados para el TFG «Sobre el nuevo estándar de encapsulado de clave (KEM) post–cuántico» del departamento de matemáticas de la ETSII. Realizado por Gabriel Vacaro e Ignacio Warleta, alumnos de ingenieria del software.

El proyecto tiene como objetivo complementar el trabajo de documentación e investigación que se ha realizado sobre el nuevo estándar del NIST KYBER-KEM de una forma didáctica. De forma que se pueda entender completamente la primitiva matemática en la que se basa la mayoría de algoritmos de criptografia post-cuántica, los retículos. Así como los problemas en los que se sustentan estos algoritmos.

Los elementos principales del trabajo incluyen:
- Notebook sobre LattPy, una biblioteca de Python desarrollada por Dylan Jones que nos sirve para introducir el concepto de retículo y aprender a trabajar con ellos en python.
- Notebook sobre problemas relacionados con los retículos, donde se encuentran las implementaciones de los problemas CVP, SVP y LWE. Explicados paso a paso.
- Notebook sobre problemas relacionados con los anillos, donde se encuentran las implementaciones de los problemas MLWE y RLWE. Explicados paso a paso.

## Instalación

Para ejecutar este proyecto, necesitas seguir estos pasos:

1. Instalar Miniconda en el siguiente enlace: https://docs.conda.io/projects/conda/en/stable/

2. Iniciar el ejecutable AnacondaPrompt o una ventana de la terminal para crear un entorno virtual especifico:
   ```bash
   conda create -n <env-name>

3. Activar el entorno virtual creado
   ```bash
   conda activate <env-name>

4. Descargar dependencias necesarias:
   ```bash
   conda install matplotlib
   conda install numpy
   pip install lattpy

5. Descargar jupyter notebook:
   ```bash
   pip install jupyter

6. Ejecutarlo con el comando:
   ```bash
   jupyter notebook

7. Clonar este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/ignaciowarleta/repo-TFG.git

8. Seleccionar desde la ventana de jupyter notebook el notebook del repositorio que se quiera usar.

   
