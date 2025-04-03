# ML_ProyectBreakII - **Versión en Español**
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
- **`src/models`**: Modelos guardados en formato `.pkl`, `.joblib`.

---------------------------------------------------------------------------------------
# ML_ProyectBreakII - **English Version**

# Spotify Song Popularity Prediction Project

## Description

In this study, the goal is to predict the **popularity** of new songs that enter Spotify based on various characteristics of the songs. The project focuses on data analysis and the application of Machine Learning techniques to tackle a real-world problem in the music industry.

## Dataset

I have chosen the *"**Spotify**"* dataset because it contains relevant information about the songs, such as:

- Release year
- Valence (mood of the song)
- Duration
- Danceability
- Whether the song is acoustic or not
- Popularity (our target variable)
- Among other important variables

This dataset includes both numerical and categorical variables, which allows for the application of preprocessing techniques like PCA (Principal Component Analysis) for dimensionality reduction (unsupervised technique), as well as regression models (supervised techniques) to make predictions about the popularity of the songs.

## Business Problem

Popularity is a continuous variable, making the problem a **regression** task rather than a **classification** task. Predicting a song's popularity is highly relevant in the music industry, as music platforms like Spotify greatly benefit from being able to anticipate which songs will become popular and, consequently, adjust their recommendation algorithms.

This type of analysis and prediction is useful in real life, especially for artists, producers, and record labels who want to understand which characteristics might influence a song's success and improve their marketing strategy.

## Project Structure

The project structure is as follows:

- **`src/data_sample`**: Contains a sample of the dataset used (≤ 5MB).
- **`src/img`**: Images generated throughout the project (charts, diagrams, etc.).
- **`src/notebooks`**: Notebooks used for testing and exploration.
- **`src/results_notebook`**: Final notebook summarizing the process and containing the model evaluation.
- **`src/models`**: Saved models in `.pkl`, `.joblib` format.

