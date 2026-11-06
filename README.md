# Google Machine Learning Crash Course - Ejercicios Prácticos

¡Hola! Soy Oscar. En este repositorio recopilo los cuadernos y scripts de código que he ido desarrollando como parte de mi formación en el **Machine Learning Crash Course** oficial de Google.

El objetivo de esta colección no es simplemente replicar la teoría, sino asentar las bases del Machine Learning mediante la práctica. He adaptado y simplificado los laboratorios originales de Google Colab para escribir un código más limpio, directo y enfocado en la comprensión real de cada algoritmo y técnica de procesamiento de datos.

## 📂 Contenido del Repositorio

Este repositorio incluye la resolución de los siguientes laboratorios que completan el curso:

1. **Regresión Lineal (`01_Regresion_Lineal_Taxi.ipynb`)**
   * **Objetivo:** Predecir la tarifa de un taxi en Chicago.
   * **Conceptos:** Regresión lineal simple y multivariable, ajuste de hiperparámetros (Learning Rate, Epochs, Batch Size), curvas de pérdida e interpretación del error cuadrático medio (RMSE).

2. **Clasificación Binaria (`02_Clasificacion_Binaria_Arroz.ipynb`)**
   * **Objetivo:** Clasificar dos variedades de arroz (Cammeo vs. Osmancik) según sus dimensiones geométricas.
   * **Conceptos:** Función de activación Sigmoide, entropía cruzada binaria (Binary Crossentropy), umbrales de decisión y análisis de la Matriz de Confusión (Accuracy, Precision, Recall).

3. **Estadística de Datos Numéricos (`03_Estadisticas_Datos_Numericos.ipynb`)**
   * **Objetivo:** Exploración inicial (EDA) del dataset *California Housing*.
   * **Conceptos:** Análisis de distribuciones (sesgo/colas largas), interpretación de cuartiles y detección visual de anomalías mediante histogramas y diagramas de caja (*boxplots*).

4. **Limpieza y Valores Anómalos (`04_Limpieza_y_Valores_Anomalos.ipynb`)**
   * **Objetivo:** Tratar valores nulos y atípicos extremos (*outliers*) en los datos de viviendas.
   * **Conceptos:** Imputación de datos faltantes (uso de la mediana) y técnica de *Clipping* para acotar valores extremos y mejorar el entrenamiento de futuros modelos.

5. **Equidad y Sesgo en ML (`05_Equidad_y_Sesgo_Adult_Census.ipynb`)**
   * **Objetivo:** Predecir ingresos (>50K) utilizando el *Adult Census Dataset* y auditar el modelo para detectar prejuicios demográficos.
   * **Conceptos:** Partición de datos por atributos sensibles (género), ajuste de umbrales de decisión en predicciones desequilibradas, y evaluación de sesgo histórico mediante el análisis de discrepancias en la Exactitud, Precisión y Exhaustividad (Recall) entre subgrupos.

## 🛠️ Stack Tecnológico
Para la resolución de todos estos ejercicios he utilizado el siguiente ecosistema de librerías en Python:
* **TensorFlow / Keras:** Creación, compilación y entrenamiento de los modelos predictivos.
* **Pandas & NumPy:** Carga de datasets (CSV), manipulación de DataFrames, prevención de filtraciones de datos (*data leakage*) y transformaciones matemáticas.
* **Scikit-Learn:** Evaluación avanzada de modelos (ej. `confusion_matrix`, `precision_score`, `recall_score`).
* **Matplotlib & Seaborn:** Visualización de datos, matrices de correlación, curvas de aprendizaje y comparativas demográficas.

---
*Repositorio creado y mantenido por Oscar para documentar el progreso y aprendizaje continuo en el ámbito de la Inteligencia Artificial y el Data Science.*
