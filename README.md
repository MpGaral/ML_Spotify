# ML_ProyectBreakII
# Proyecto de Predicción de Popularidad de Canciones en Spotify

## Descripción

En este estudio, el objetivo es predecir la **popularidad** de nuevas canciones que entren en Spotify a partir de diferentes características de estas. El proyecto se centra en el análisis de datos y la aplicación de técnicas de Machine Learning para abordar un problema real en la industria de la música.

## Dataset

He elegido el conjunto de datos *"**Spotify**"* porque contiene información relevante sobre las canciones, como:

- Año de lanzamiento
- Valencia (estado de ánimo de la canción)
- Duración
- Bailabilidad
- Si la canción es acústica o no
- Popularidad (nuestra variable objetivo)
- Entre otras variables importantes

Este dataset incluye tanto variables numéricas como categóricas, lo que permite aplicar técnicas de preprocesamiento como PCA (análisis de componentes principales) para reducción de dimensionalidad (técnica no supervisada), así como modelos de regresión (técnicas supervisadas) para hacer predicciones sobre la popularidad de las canciones.

## Problema de Negocio

La popularidad es una variable continua, lo que convierte el problema en uno de **regresión** en lugar de **clasificación**. Predecir la popularidad de una canción es una tarea muy relevante en la industria musical, ya que las plataformas de música como Spotify se benefician enormemente de poder anticipar qué canciones se volverán populares y, en consecuencia, ajustar sus algoritmos de recomendación.

Este tipo de análisis y predicción es útil en la vida real, especialmente para los artistas, productores y compañías discográficas que desean saber qué características podrían influir en el éxito de una canción y mejorar su estrategia de marketing.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

- **`src/data_sample`**: Contiene una muestra del dataset utilizado (≤ 5MB).
- **`src/img`**: Imágenes generadas durante el proyecto (gráficas, diagramas, etc.).
- **`src/notebooks`**: Notebooks utilizados para pruebas y exploración.
- **`src/results_notebook`**: Notebook final que resume el proceso y contiene la evaluación del modelo.
- **`src/models`**: Modelos guardados en formato `.pkl`, `.joblib`, etc.
- **`src/utils`**: Funciones auxiliares o clases para el desarrollo del proyecto.
