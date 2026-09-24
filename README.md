# S100 — Equipo 2 · Proyecto Final

**Gasto en salud y esperanza de vida (América + Europa, 2000–2024)**

Análisis de ciencia de datos del curso *Introducción a la Ciencia de Datos* (S100), Universidad Tecnológica de Panamá. Se evalúa si un mayor gasto en salud per cápita se asocia con mayor esperanza de vida, controlando por PIB, año y continente, mediante un baseline, un árbol de regresión y un kNN.

## Archivos principales

- `S100_Equipo2_Parte2.ipynb` — cuaderno del análisis completo
- `health_panel.csv` — datos (panel país-año)

## Cómo ejecutar el cuaderno

### Google Colab

1. Abre el `.ipynb` en [Google Colab](https://colab.research.google.com/). (Dentro del archivo esta la opción para abrirlo en Google Colab)
2. En el panel izquierdo, ve a **Archivos** y sube `health_panel.csv` a la carpeta de trabajo de la sesión (la raíz del entorno, junto al cuaderno).
3. Menú **Entorno de ejecución → Ejecutar todo**.

No hace falta instalar librerías: Colab ya incluye `pandas`, `numpy`, `matplotlib`, `seaborn` y `scikit-learn`.

### VS Code (u otro entorno local)

1. Clona o descarga este repositorio.
2. Coloca `health_panel.csv` en la misma carpeta que el cuaderno.
3. (Recomendado) Crea un entorno virtual e instala dependencias:

"```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS / Linux:
source .venv/bin/activate

pip install pandas numpy matplotlib seaborn scikit-learn jupyter"

4.Abre el .ipynb en VS Code, selecciona el kernel del entorno e ejecuta todas las celdas en orden.

También puedes instalar las librerías en el Python del sistema con el mismo pip install ... si no usas entorno virtual.

## Requisitos

Python 3.9+
pandas, numpy, matplotlib, seaborn, scikit-learn

## Equipo 2
Miguel Aparicio · Valerie Brenes · Anthony Castillo
