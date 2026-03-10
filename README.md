# challenge3_telecomX_parte2

![832d01c5-aa1f-4a72-894b-9bb18b8d2a00](https://github.com/user-attachments/assets/5d859c48-e0f4-48ac-ae90-ccde58ca68b8)

# 📊 Predicción de Cancelación de Clientes – Telecom X

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de **Machine Learning** capaces de predecir la probabilidad de cancelación (*churn*) de clientes de la empresa **Telecom X**.

A partir del análisis de los datos históricos de clientes, se busca identificar patrones que permitan anticipar qué usuarios presentan mayor riesgo de abandonar el servicio, facilitando así la implementación de **estrategias de retención**.

---

## 🎯 Objetivos

* Analizar y preparar el dataset de clientes de Telecom X.
* Identificar variables relevantes para la predicción de cancelación.
* Construir modelos de Machine Learning para clasificación.
* Evaluar el desempeño de los modelos mediante diferentes métricas.
* Analizar los resultados para apoyar la toma de decisiones estratégicas.

---

## 🗂️ Estructura del Proyecto

```
TelecomX-Churn-Prediction
│
├── data
│   └── dataset limpio de Telecom X
│
├── notebooks
│   └── Challenge3_TelecomX_LATAM_Parte2.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## ⚙️ Preparación de los Datos

En la primera etapa del proyecto se realizó el proceso de **preparación del dataset** para su uso en modelos de Machine Learning.

Las principales tareas realizadas fueron:

* Exploración del dataset y revisión de su estructura.
* Identificación de tipos de datos y valores faltantes.
* Eliminación de variables no relevantes (por ejemplo `customerID`).
* Codificación de variables categóricas a formato numérico.
* Verificación y tratamiento de valores nulos.
* Normalización de variables numéricas.
* División del dataset en **conjunto de entrenamiento y prueba**.

Este proceso permitió obtener un **dataset limpio y estructurado**, adecuado para la fase de modelado.

---

## 🤖 Modelos Utilizados

Se implementaron dos modelos de clasificación:

* **Regresión Logística**
* **Árbol de Decisión**

Estos modelos permiten analizar el comportamiento de cancelación de clientes y generar predicciones sobre el riesgo de abandono del servicio.

---

## 📈 Métricas de Evaluación

Para evaluar el desempeño de los modelos se utilizaron las siguientes métricas:

* **Accuracy**
  Proporción total de predicciones correctas realizadas por el modelo.

* **Precision**
  Mide qué tan precisas son las predicciones positivas realizadas por el modelo.

* **Recall**
  Indica la capacidad del modelo para identificar correctamente a los clientes que realmente cancelan el servicio.

* **F1-score**
  Combina *precision* y *recall* en una sola métrica equilibrada.

Además, se utilizó la **matriz de confusión** para analizar en detalle los resultados de clasificación, identificando:

* Verdaderos positivos
* Verdaderos negativos
* Falsos positivos
* Falsos negativos

---

## 🧰 Tecnologías Utilizadas

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📊 Resultados Esperados

Los modelos desarrollados permiten identificar clientes con **alto riesgo de cancelación**, lo que facilita a la empresa:

* Implementar estrategias de retención
* Mejorar la experiencia del cliente
* Reducir la tasa de abandono

---

## 🚀 Posibles Mejoras Futuras

* Implementar modelos más avanzados como:

  * Random Forest
  * Gradient Boosting
  * XGBoost
* Realizar ajuste de hiperparámetros.
* Analizar la importancia de variables.
* Construir un dashboard de visualización.

---
