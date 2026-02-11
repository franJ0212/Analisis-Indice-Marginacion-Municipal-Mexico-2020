# Análisis del Índice de Marginación Municipal (México, 2020)

Este repositorio documenta un ejercicio de análisis aplicado sobre el índice de marginación municipal con datos oficiales de CONAPO/INEGI. El enfoque principal es mostrar el proceso técnico: preparación de datos, reducción de dimensionalidad (PCA), construcción de un índice alternativo y visualización territorial de resultados.

## Objetivo del trabajo

Evaluar una forma alternativa de construir el índice de marginación usando los 9 indicadores base de CONAPO, comparar resultados con el índice oficial y discutir posibles mejoras metodológicas.

## Estructura del repositorio

- `Ejercicio3.ipynb`
  - Notebook principal del análisis.
  - Incluye carga y limpieza de datos, estandarización, PCA, exploración de componentes, comparación con el índice oficial y generación de gráficas.
  - Integra análisis tabular y visual (incluyendo mapas y figuras de apoyo).

- `IMM_2020.xls`
  - Base de datos fuente a nivel municipal.
  - Contiene variables de marginación 2020 (indicadores base, índice oficial y categorías).

- `Reporte_E3.docx`
  - Reporte ejecutivo con hallazgos, interpretación y conclusiones en formato de entrega.
  - Diseñado para una audiencia no técnica, con respaldo analítico en anexos/figuras.

- `Figura3_1.png` a `Figura3_6.png`
  - Salidas gráficas del análisis.
  - Se usan como evidencia visual para comparar patrones, componentes principales y comportamiento del �ndice alternativo.

- `national/`
  - Insumos geoespaciales usados para representación territorial.
  - Archivos `.shp` para límites municipales y estatales:
    - `national/00mun.shp`
    - `national/national_estatal.shp`

## Herramientas y librerias usadas

Python (Jupyter) con librerias como:

- `pandas`, `numpy`
- `scikit-learn` (PCA, estandarización)
- `matplotlib`, `seaborn`, `plotly`
- `geopandas` (visualización espacial)

## Cómo reproducir el análisis

1. Crear/activar un entorno de Python con dependencias de ciencia de datos y geoespacial.
2. Abrir `Ejercicio3.ipynb`.
3. Ejecutar celdas en orden para reproducir tablas, métricas y figuras.

## Nota

Este repositorio corresponde a un ejercicio académico aplicado, presentado aquí como muestra de trabajo técnico en análisis de datos, modelado estadístico y comunicación de resultados.
