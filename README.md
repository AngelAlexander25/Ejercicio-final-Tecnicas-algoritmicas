# Ejercicio Final: Resolución de Sudokus con Backtracking

Este proyecto implementa un algoritmo de **backtracking** para resolver Sudokus, proporcionando además una visualización paso a paso del proceso de resolución. El código está escrito en Python y diseñado para ejecutarse en Google Colab o cualquier entorno compatible con Jupyter Notebooks.

---

## **Descripción**
El algoritmo utiliza técnicas de búsqueda exhaustiva para encontrar la solución de un Sudoku de 9x9, asegurando que se cumplan todas las reglas del juego. El proyecto también incluye funciones para:
- Generar tableros de Sudoku con distintos niveles de dificultad.
- Validar la consistencia del tablero inicial.
- Visualizar el progreso de la resolución con gráficos interactivos.
- Medir el rendimiento del algoritmo en términos de tiempo y memoria.

---

## **Características**
- **Generación dinámica de Sudokus**: Tableros generados con niveles de dificultad ajustables (bajo y medio).
- **Visualización paso a paso**: Uso de `matplotlib` para mostrar cómo el algoritmo llena el tablero.
- **Medición de rendimiento**: Análisis de tiempo de ejecución y uso de memoria para cada prueba.
- **Fácil personalización**: Código modular y bien documentado.

---

## **Estructura del Proyecto**
- `Ejercicio_final.ipynb`: Notebook principal que contiene todo el código.
- Librerías utilizadas:
  - `py-sudoku`: Generación de Sudokus.
  - `matplotlib`: Visualización de tableros.
  - `psutil`: Medición del uso de memoria.

---
## **Requisitos**
Asegúrate de instalar las dependencias necesarias antes de ejecutar el notebook:

```bash
!pip install py-sudoku
!pip install psutil

