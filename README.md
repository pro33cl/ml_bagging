# 🧠 Modelos Bagging para Predicción de Renuncias de Clientes

Notebook: ml_bagging.ipynb

📄 Descripción General

Este notebook desarrolla un flujo completo basado en árboles de decisión, SVM y métodos de Bagging para predecir la renuncia de clientes. Se incluye balanceo de clases con SMOTE, análisis exploratorio, construcción de modelos base, BaggingClassifier, RandomForest y una búsqueda exhaustiva de hiperparámetros.

📂 Contenidos del Notebook

1️⃣ Análisis inicial del dataset

- Carga del dataset de clientes.
- Exploración estadística y visual.
- Correlaciones y heatmap.

2️⃣ Modelos base

- Árboles de decisión.
- Modelos SVM con distintos kernels.
- Métricas iniciales de comparación.

3️⃣ Balanceo con SMOTE

- Oversampling para corregir desbalance.
- División train/test.

4️⃣ Bagging

- Implementación de BaggingClassifier con DecisionTree y SVM.
- Uso de 200 muestras bootstrap (T).
- Evaluación sobre test (accuracy, precision, recall, F1, ROC, AUC).

5️⃣ Random Forest

- Entrenamiento del modelo de ensamblado RF.
- Comparación del desempeño vs Bagging.

6️⃣ Optimización con GridSearchCV

- Búsqueda de hiperparámetros para el Random Forest.
- Análisis de resultados y métricas ROC/AUC.

7️⃣ Identificación de clientes críticos

- Selección de los 15 clientes con mayor probabilidad de renunciar.

🛠️ Tecnologías Utilizadas

Python 3

- NumPy
- Pandas
- Matplotlib / Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- Joblib

▶️ Cómo Ejecutar el Notebook

1. Clonar el repositorio:

- git clone <URL>
- cd <repo>

2. Instalar dependencias:
   
- pip install -r requirements.txt

3. Ejecutar:
   
- jupyter notebook ml_bagging.ipynb

🎯 Objetivo del Proyecto

Construir modelos Bagging para predecir la renuncia de clientes, comparando arquitecturas y seleccionando los hiperparámetros óptimos para maximizar el rendimiento.

📬 Contacto

Proyecto desarrollado por Héctor Rubilar Valenzuela.
