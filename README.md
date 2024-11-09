
# Proyecto TENIS

Este repositorio contiene el proyecto **TENIS**, una práctica de la asignatura **Fundamentos de Sistemas Operativos (FSO)**. El objetivo principal de este proyecto es el aprendizaje y la implementación de conceptos fundamentales en el manejo de **threads** y **procesos** en sistemas operativos, así como la **sincronización** mediante **semáforos**, **buzones** y **paso de mensajes**.

## Descripción

La práctica **TENIS** simula un entorno controlado donde se pone en práctica el uso de diferentes mecanismos de sincronización en programación concurrente. Durante el desarrollo del proyecto, se exploran los siguientes temas clave:

- **Creación y gestión de threads y procesos**.
- **Sincronización de threads y procesos** mediante el uso de:
  - Semáforos
  - Buzones
  - Paso de mensajes

Esta simulación permite entender cómo los sistemas operativos administran múltiples tareas concurrentes y cómo se puede asegurar que dichas tareas colaboren sin interferencias ni condiciones de carrera.

## Requisitos

Para ejecutar este proyecto, se requiere tener un entorno de desarrollo compatible con C/C++ o cualquier otro lenguaje especificado por el profesor de la asignatura, así como un compilador adecuado para dicho lenguaje.

### Dependencias

- **Sistema Operativo**: Compatible con sistemas basados en UNIX/Linux (recomendado para un manejo óptimo de threads y semáforos).
- **Compilador**: GCC o compatible para la compilación del proyecto.
- **Bibliotecas adicionales**: Las bibliotecas estándar de manejo de threads y sincronización según el lenguaje.

## Instrucciones de uso

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/usuario/TENIS.git
   cd TENIS
   ```

2. **Compilar el proyecto**:
   - Dependiendo del archivo `Makefile` o instrucciones adicionales, compilar con:
     ```bash
     make
     ```
   - O directamente usando el compilador adecuado:
     ```bash
     gcc -o tenis main.c -lpthread
     ```

3. **Ejecutar la simulación**:
   ```bash
   ./tenis
   ```

## Estructura del Proyecto

- `src/`: Contiene el código fuente del proyecto.
- `include/`: Archivos de cabecera.
- `docs/`: Documentación del proyecto, si corresponde.
- `README.md`: Este archivo, con las instrucciones básicas del proyecto.

## Autores

Proyecto realizado por:

- Eduard Vericat Batalla
- Alfonso Sanchez Ferrer

## Licencia

Este proyecto está destinado únicamente a fines académicos en el contexto de la asignatura de Fundamentos de Sistemas Operativos (FSO).
