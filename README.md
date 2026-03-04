# coffee-quality-analysis
Predicción de Calidad del Café: Aplicación de Algoritmos Supervisados

Este proyecto se centra en la creación de un modelo predictivo para estandarizar la calidad del café dominicano. Utilizando datos del Instituto Dominicano del Café (INDOCAFE), desarrollamos un análisis para predecir la calificación final de las muestras basándonos en sus características químicas y sensoriales.

El Problema

Para el sector exportador de la República Dominicana, es vital asegurar que el café cumpla con estándares específicos. El reto consistió en entrenar modelos que utilicen variables como acidez, aroma y cuerpo para determinar la calidad del grano de forma objetiva y automatizada.

Lo que hicimos
Análisis de variables: Exploramos cómo factores sensoriales influyen en la puntuación final de la taza.

Modelado Supervisado: Implementamos y comparamos tres algoritmos diferentes:

Regresión Lineal

Support Vector Regression (SVR)

K-Nearest Neighbors (KNN)

Evaluación: Comparamos el rendimiento de los modelos utilizando métricas de error (RMSE) y precisión (R2) para determinar cuál es el más confiable para INDOCAFE.

Herramientas Utilizadas
Python

Pandas y NumPy para el procesamiento de datos.

Scikit-learn para el entrenamiento y evaluación de modelos supervisados.

Matplotlib/Seaborn para la visualización de resultados.

Cómo utilizar este repositorio

Abre el archivo Trabajo_en_equipos_Aplicación_de_Algoritmos_Supervisados.ipynb.

Se recomienda su ejecución en Google Colab para facilitar el manejo de las librerías.

El notebook incluye la comparación final de los modelos para identificar el de mejor desempeño.
