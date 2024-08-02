# TPs

Los trabajos prácticos fueron realizados en conjunto con **Agustín Vallcorba** y [Nicolás García](https://github.com/nicolasg98).

- **TP1:** Se centró en predecir cancelaciones de reservas de hotel utilizando técnicas de ciencia de datos. Se dividió en dos etapas principales:

  1. **Análisis Exploratorio y Preprocesamiento:** Se evaluaron y limpiaron los datos mediante el análisis de variables, visualización, y el tratamiento de datos faltantes y valores atípicos.

  2. **Clasificación y Predicción:**
  Se entrenaron modelos con el fin de predecir si una reserva de hotel va a ser cancelada o no, con resultados presentados en una competencia de Kaggle.
     - **Árboles de Decisión:** Se realizó la optimización y evaluación a través de k-fold cross-validation.
     - **Ensamble de Modelos:** Se construyeron varios clasificadores como KNN, SVM, Random Forest, y XGBoost, además de ensambles (Voting y Stacking).
     - **Redes Neuronales:** Se diseñó y ajustó una red neuronal para mejorar el rendimiento.                


- **TP2:** Se utilizó una colección de críticas cinematográficas en español para clasificar su sentimiento como positivo o negativo.

  Se crearon modelos de clasificación que analicen texto en lenguaje natural y detecten el sentimiento de forma binaria. Se realizó un preprocesamiento del texto utilizando "bag of words" y otros métodos para convertir texto en vectores.

  Los modelos que se construyeron son:

  - **Bayes Naïve**
  - **Random Forest**
  - **XGBoost**
  - **Red Neuronal** utilizando Keras y TensorFlow
  - **Ensamble** de al menos tres modelos anteriores

  Para cada modelo, se realizó una búsqueda de hiperparámetros para optimizar su desempeño en un conjunto de prueba local. Luego, los resultados fueron presentados tambien en otra competencia de Kaggle.
