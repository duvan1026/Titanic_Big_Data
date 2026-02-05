# 🚢 Titanic Data Science Project: Análisis Multimodelo de Supervivencia

## 📋 Descripción del Proyecto
En este proyecto, he desarrollado un ecosistema de aprendizaje automático para predecir la supervivencia de los pasajeros del Titanic. Mi enfoque no se limitó a un solo algoritmo; exploré la trazabilidad de los datos desde el aprendizaje no supervisado (**Clustering**) hasta el aprendizaje profundo (**Deep Learning**), permitiendo una comparación científica entre modelos probabilísticos, lógicos y neuronales.



## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.14
* **Librerías Principales:** `Pandas`, `Scikit-Learn`, `NumPy`, `Matplotlib`.
* **Modelos Implementados:** * Naive Bayes (Probabilístico)
    * Árboles de Decisión (Lógico)
    * **K-Nearest Neighbors - K-NN (Ganador)**
    * Multilayer Perceptron - MLP (Neuronal)
    * Autoencoder (Deep Learning / Reconstrucción)

## 🚀 Flujo de Trabajo

### 1. Preprocesamiento y Limpieza
Realicé una curación de datos exhaustiva, tratando valores nulos en la edad, codificando variables categóricas (sexo, puertos de embarque) y escalando las variables numéricas para asegurar la convergencia de las redes neuronales.

### 2. Análisis de Perfiles (Clustering)
Antes de predecir, utilicé técnicas de agrupamiento para entender la jerarquía social del barco. Esto me permitió identificar que el género y la clase eran los ejes conductores de la estructura de datos.

### 3. Competencia de Modelos (Clasificación)
Sometí al dataset a una competencia de 5 algoritmos. Utilicé **GridSearchCV** para la sintonía fina de hiperparámetros, optimizando cada modelo para obtener su máximo rendimiento.



## 📊 Resultados y Evaluación
Tras validar los modelos con un conjunto de prueba, obtuve los siguientes resultados de precisión (**Accuracy**):

| Modelo | Precisión (Accuracy) | Estado |
| :--- | :--- | :--- |
| **K-Nearest Neighbors (K-NN)** | **83.21%** | **Modelo Seleccionado** |
| Multilayer Perceptron (MLP) | 82.09% | Finalista |
| Autoencoder Clasificador | 80.60% | Finalista |
| Árbol de Decisión | 80.60% | Competitivo |
| Naive Bayes | 77.99% | Base Line |

### ¿Por qué elegí K-NN?
Aunque implementé arquitecturas de Redes Neuronales avanzadas, **mi análisis determinó que K-NN es el modelo más asertivo**. Su capacidad para clasificar basándose en la similitud de perfiles capturó de manera más orgánica la realidad del Titanic, donde pasajeros con características similares (vecinos sociales) tendieron a compartir el mismo destino.

## 🧠 Innovación: Autoencoders
Implementé un **Autoencoder** con un doble propósito:
1. **Validación:** Confirmar la integridad de mis variables mediante un bajo Error Cuadrático Medio (MSE).
2. **Clasificación Profunda:** Comprimir la información en un espacio latente de 5 dimensiones para predecir la supervivencia desde una perspectiva de aprendizaje no supervisado.



## 💡 Conclusión Final
Este proyecto me ha permitido demostrar que la tragedia del Titanic tuvo una **estructura matemática subyacente**. A través de mi investigación, he logrado construir un motor de predicción que no solo acierta en un 83.21%, sino que también ofrece un índice de veracidad estructural sobre la calidad de los datos de cada pasajero.

---

### 📂 Estructura del Repositorio
* `Titanic_Analysis.ipynb`: Cuaderno principal con todo el pipeline de datos.
* `data/`: Conjuntos de entrenamiento y test real.
* `results/`: Tabla maestra con las predicciones consolidadas de todos los modelos.

**Desarrollado por Duvan Castro** *Analista de Datos / Entusiasta de la Inteligencia Artificial*