# Challenge-Telecom-X-2

# 🤖 Telecom X - Predicción de Churn con Machine Learning (Parte 2)

Esta es la segunda fase de mi proyecto de Data Science para el challenge del programa ONE. Tras finalizar el análisis exploratorio, en esta etapa construimos y entrenamos modelos de Machine Learning para predecir qué clientes tienen mayor riesgo de abandonar la empresa y entender qué variables matemáticas impulsan esa decisión.

## 🛠️ Tecnologías y Dependencias Nuevas
Además de `pandas` y `matplotlib`, para esta etapa incorporamos herramientas predictivas:
* `scikit-learn` (para los algoritmos y la división de datos)
* `imbalanced-learn` (para aplicar SMOTE)

## 📂 Estructura del Modelado
1. **Preprocesamiento Avanzado:** Transformación de variables de texto a numéricas mediante *One-Hot Encoding* (`pd.get_dummies`).
2. **División y Escalamiento:** Separación de datos en entrenamiento (Train) y prueba (Test), y estandarización de variables.
3. **Balanceo de Clases:** Uso de la técnica **SMOTE** para equilibrar el dataset y evitar sesgos hacia la clase mayoritaria (clientes que se quedan).
4. **Entrenamiento y Evaluación:** Implementación de *Regresión Logística*, *Random Forest* y *Support Vector Machine (SVM)*.
5. **Feature Importance:** Extracción de las variables más críticas matemáticamente (ej. Antigüedad y Tipo de Contrato) para generar estrategias de retención.

## 🚀 Cómo ejecutar esta fase
1. Asegúrate de haber corrido primero todas las celdas de la Parte 1 (Limpieza y EDA).
2. Si estás en un entorno local, verifica tener instalada la librería para balancear datos ejecutando `pip install imbalanced-learn` en tu terminal.
3. Ejecuta las celdas de Machine Learning en orden para entrenar los modelos y ver los gráficos de importancia de variables.
