# TPs

Los trabajos prácticos fueron realizados en conjunto con **Agustín Vallcorba** y [Nicolás García](https://github.com/nicolasg98). A continuación se detallan los principales objetivos y logros de cada TP:

- **TP1:** Este trabajo se centró en predecir cancelaciones de reservas de hotel utilizando técnicas de ciencia de datos. Se dividió en dos etapas principales:

  1. **Análisis Exploratorio y Preprocesamiento:** Se evaluaron y limpiaron los datos mediante el análisis de variables, visualización, y el tratamiento de datos faltantes y valores atípicos.

  2. **Clasificación y Predicción:**
     - **Árboles de Decisión:** Se realizó la optimización y evaluación a través de k-fold cross-validation.
     - **Ensamble de Modelos:** Se construyeron modelos como KNN, SVM, Random Forest, y XGBoost, además de ensambles (Voting y Stacking).
     - **Redes Neuronales:** Se diseñó y ajustó una red neuronal para mejorar el rendimiento.

  El objetivo fue aplicar técnicas de análisis de datos y modelos de clasificación para predecir cancelaciones, con resultados presentados en una competencia de Kaggle.

- **TP2:** En este trabajo, se utilizó una colección de críticas cinematográficas en español para clasificar su sentimiento como positivo o negativo.

  El objetivo fue construir modelos de clasificación que analicen texto en lenguaje natural y detecten el sentimiento de forma binaria. Se realizó un preprocesamiento del texto utilizando "bag of words" y otros métodos para convertir texto en vectores.

  Se construyeron los siguientes modelos:

  - **Bayes Naïve**
  - **Random Forest**
  - **XGBoost**
  - **Red Neuronal** utilizando Keras y TensorFlow
  - **Ensamble** de al menos tres modelos anteriores

  Para cada modelo, se realizó una búsqueda de hiperparámetros para optimizar su desempeño en un conjunto de prueba local.
