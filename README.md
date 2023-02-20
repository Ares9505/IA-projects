# IA-projects #
Proyectos de inteligencia artificial:

## Práctica 1. Reconocimiento de estado de ánimo en audio ##
Se aplican técnicas de procesamiento de voz y se genera un modelo de clasificación de moods (estados emocionales)
Para ellos se usa características de audio como:
- mfccs 
- tasa de cruces por cero
- chroma
- ritmo
- energía
- centro de gravedad

Se entrenaron 4 modelos:
- Suport Vector Machine (SVM)
- Decision Tree 
- Random Forest
- K-Nearest Neighbor (KNN)


## Practica 2. Reconocimiento de vocales en lenguaje de señas ##
Se aplican técnicas de procesamiento de imágenes y se genera un modelo de clasificación de letras (cinco vocales) de la Lengua de Señas Mexicana.
Esta práctica se divide en dos fases:
1. Entrenamiento y evaluación interna del modelo de clasificación (Naive Bayes)
2. Validación externa del modelo con nuevos datos.
Notas: Se usa la libreria cvzone para la extraccion de landmarks (marcas de referencia) de manos en imagenes.


