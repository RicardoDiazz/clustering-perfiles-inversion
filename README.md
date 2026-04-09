Análisis de Perfiles de Inversión (Clustering de Activos)
Este repositorio contiene el avance del proyecto de Machine Learning enfocado en la segmentación de activos financieros utilizando aprendizaje no supervisado.

Objetivo del Proyecto
Identificar agrupaciones (clusters) de activos financieros basados en sus perfiles de riesgo y retorno diarios, superando las clasificaciones sectoriales tradicionales mediante el uso de PCA y K-means.

Estructura del Repositorio
data/: Contiene el dataset dataset_inversiones.csv extraído de Yahoo Finance.

notebooks/: Notebook de Google Colab con el pipeline completo de preprocesamiento, optimización (Método del Codo) y modelado.

reports/: Informe técnico detallado en formato PDF con el análisis de resultados y matriz de limitaciones.

Stack Tecnológico

Librerías principales: yfinance, pandas, scikit-learn (PCA, KMeans), matplotlib.

Entorno: Google Colab.

Resultados Preliminares
A la fecha, el modelo ha identificado 4 perfiles de inversión óptimos que logran capturar la dinámica de volatilidad del mercado con una varianza explicada del 64.98%.

Autor
Ricardo Delgadillo Diaz

Estudiante de Matemáticas y ciencia de datos - Universidad El Bosque
