# movie_review_classifier
Creación de modelos de machine learning para clasificar las reseñas de películas como positivas o negativas.
***Proyecto desarrollado como evaluación final del sprint 15 (machine learning para textos) del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. El objetivo es entrenar un modelo para detectar las críticas negativas de forma automática. Para lograrlo, se utilizaron un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad para construir un modelo para clasificar las reseñas positivas y negativas. El modelo debía alcanzar un valor F1 de al menos 0.85.

## Objetivo del proyecto
Crear un modelo de machine learning de clasifiación que obtenga un score F1 mayor a 0.85

## Modelos de machine learning creados
- Logistic Regression
- Random Forest Classifier
- Light Gradient Boosting Machine (Light GBM)

## Librerías principales utilizadas
- spacy
- NLTK
- Sklearn

## Resultados
- Se logró un score **F1 de 0.88** con el modelo de regresión logística, **4% mejor** que el mínimo solicitado.
- Se utilizó una estrategia de limpieza del corpus de texto que eliminara simbolos, letras repetidas más de tres veces, y letras sueltas para mejorar la predicción.
- Se utilizó una estrategia de lematización en bloques para optimizar el rendimiento de SpaCy. 