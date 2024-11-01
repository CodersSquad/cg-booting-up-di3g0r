[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850760&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

# Instrucciones para Ejecutar Archivos

## Requisitos Previos

- **Python 3** Instalado.
- **Pip** para instalar las dependencias de Python.

## Configuración del Entorno Virtual

1. **Clonar el proyecto** y navegar a la carpeta principal del proyecto:

   git clone https://github.com/CodersSquad/cg-booting-up-di3g0r

2. **Crear y activar Entorno Virtual**

    En este caso el entorno virtual ya esta creado, solo se tendria que activar (2da linea)

    - python -m venv myenv
    - myenv\Scripts\activate

3. **Instalar dependencias**

    pip install numpy pygame pillow moderngl pyglm objloader

4. **Ejecutar programas**

    Para ejecutar cada programa se llama:
    - python 01_hello_world.py 
    - python 06_multiple_objects.py
    - python 09_models_and_images.py 


## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs