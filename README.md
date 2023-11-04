# Laboratorio2-Grupo24-BigData

Integrantes: 
- Fernandez Achilli Franco 
- Lopez Julieta
- Wagner Cabrera Idana

# Clasificador de Canciones de Spotify

Este proyecto se centra en la creación de un clasificador de canciones de Spotify que tiene como objetivo predecir las preferencias musicales de un usuario. Utilizaremos un conjunto de datos que contiene una variedad de atributos musicales y etiquetas que indican si a un usuario le gustó o no una canción.

## Conjunto de Datos

El conjunto de datos proporcionado incluye 16 columnas, donde 13 representan atributos específicos de las canciones. Además, se incluyen columnas para el nombre de la canción y el nombre del artista. La columna "target" actúa como etiqueta, indicando las preferencias del usuario con un valor de "1" para canciones que le gustaron y "0" para las que no.

### Atributos de las Canciones

1. **Danceability**: Describe cuán adecuada es una pista para bailar basada en una combinación de elementos musicales.

2. **Energy**: Representa una medida perceptiva de intensidad y actividad.

3. **Loudness**: Es una medida general de la sonoridad de una pista en decibeles.

4. **Speechiness**: Detecta la presencia de palabras habladas en una pista.

5. **Acousticness**: Una medida de cuán acústica es una pista.

6. **Instrumentalness**: Predice si una pista no contiene voces.

7. **Liveness**: Detecta la presencia de una audiencia en la grabación.

8. **Valence**: Describe la positividad musical transmitida por una pista.

9. **Tempo**: Es la velocidad general o ritmo de una pista.

## Flujo de Trabajo

1. **Selección de Características**: Se elegirán las características óptimas para el entrenamiento de los modelos.

2. **División de Datos**: Se separarán los datos en conjuntos de entrenamiento y prueba.

3. **Modelos de Machine Learning**:
   - KNN (K-Nearest Neighbors)
   - SVM (Support Vector Machines)
   - Árbol de decisión
   - Bayes (Naive Bayes)
   - Otro modelo adicional

4. **Validación**:
   - Validación Simple
   - Validación Cruzada k-fold

5. **Evaluación de Rendimiento**:
   - Matriz de Confusión
   - Precisión, Recall y F1-score

6. **Ajuste de Hiperparámetros**:
   - Grid Search
   - Random Search

7. **Ensamble de Modelos**:
   - Votación Mayoritaria

8. **Evaluación del Rendimiento del Ensamble**:
   - Matriz de Confusión
   - Precisión, Recall y F1-score

## Informe y Comentarios

Este proyecto será desarrollado en un entorno de Notebook de Google Colab. Cada paso del proceso estará acompañado por explicaciones detalladas sobre las decisiones tomadas, técnicas utilizadas y resultados obtenidos. Se documentarán los desafíos o inconvenientes surgidos durante el desarrollo para brindar una visión completa del proceso.

## Conclusiones

Al finalizar este proyecto, esperamos tener un clasificador de canciones de Spotify bien entrenado y evaluado, capaz de predecir las preferencias de un usuario con precisión. 
Los resultados y conclusiones finales se incluyen en el notebook.
