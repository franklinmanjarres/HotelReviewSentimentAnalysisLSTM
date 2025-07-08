## HotelReviewSentimentAnalysisLSTM


**Clasificación de opiniones hoteleras usando redes LSTM y embeddings preentrenados**

Este proyecto implementa un modelo de clasificación de texto para predecir la polaridad (positiva/negativa) de reseñas hoteleras. Utiliza una red neuronal recurrente (LSTM) con **embeddings preentrenados** de **Word2Vec** para procesar texto en inglés.

---

##  Características principales

-  **Modelo LSTM**: Utiliza una red neuronal recurrente para capturar dependencias secuenciales en el texto, ideal para tareas de procesamiento del lenguaje natural.
-  **Embeddings preentrenados**: Incorpora vectores de palabras entrenados con **Word2Vec** (Gensim) para representar semánticamente las palabras.
-  **Preprocesamiento robusto**: Limpieza del texto que incluye:
  - Tokenización
  - Eliminación de *stopwords*
  - Filtrado de puntuación y números
-  **Visualización**: Análisis exploratorio de la longitud de las reseñas y distribución de clases.
-  **Dataset**: Utiliza el conjunto de datos `deceptive-opinion.csv`, que contiene reseñas etiquetadas como **engañosas** o **genuinas**.

---

##  Tecnologías utilizadas

-  Python  
-  TensorFlow / Keras (modelo LSTM)  
-  Gensim (Word2Vec)  
-  NLTK (procesamiento de texto)  
-  Matplotlib (visualización)  
-  Pandas / NumPy (análisis y manipulación de datos)
