# Product-Purchase-Prediction
Este proyecto tiene como objetivo predecir si un cliente realizará una compra, utilizando variables relacionadas con comportamiento y estacionalidad mediante un modelo de machine learning interpretable.
Product Purchase Prediction

Predicción de si un cliente realizará una compra utilizando variables de comportamiento y estacionalidad mediante un modelo de machine learning interpretable.

# Objetivo

Desarrollar un modelo capaz de anticipar la probabilidad de compra de un cliente para apoyar decisiones de marketing, segmentación y campañas estacionales.

# Dataset

Dataset sintético de 5,000 registros con las siguientes variables:

Is_Winter: Indica si es temporada de invierno (0/1)
Is_Holiday_Season: Indica si es temporada de festivos (0/1)
Days_Since_Last_Purchase: Días desde la última compra
Average_Spend: Gasto promedio del cliente
Made_Purchase: Variable objetivo (0/1)
🛠️ Tecnologías utilizadas
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Streamlit (para visualización interactiva)

# Proceso
## 1. EDA (Exploratory Data Analysis)

Análisis de correlaciones entre variables para identificar factores que influyen en la compra.

## 2. Preprocesamiento

Preparación de datos para el modelo (estructura limpia y lista para entrenamiento).

## 3. Entrenamiento del modelo

Se utiliza Logistic Regression, elegida por su capacidad de interpretación directa.

Permite entender cómo cada variable impacta la probabilidad de compra.

## 4. Interpretación del modelo
Coeficientes → indican dirección del impacto
Odds Ratio → mide cuánto aumenta o disminuye la probabilidad
## 5. Evaluación

Se utilizan métricas simples:

### Accuracy
Precision
Matriz de confusión
### Resultados
Modelo final: Logistic Regression
Variables más influyentes:
Is_Holiday_Season → mayor impacto positivo
Is_Winter → aumenta la probabilidad de compra
Days_Since_Last_Purchase → impacto negativo
## Ejemplo de interpretación

Un cliente en temporada de festivos tiene mayor probabilidad de compra debido al alto peso de esta variable en el modelo.

## Evaluación del modelo

La matriz de confusión permite entender el desempeño:

Clientes correctamente identificados como compradores
Clientes que el modelo no logró predecir (falsos negativos)
Predicciones incorrectas de compra (falsos positivos)
## Valor de negocio
Identificación de clientes con alta probabilidad de compra
Optimización de campañas en temporadas clave
Mejora en la asignación de presupuesto de marketing
