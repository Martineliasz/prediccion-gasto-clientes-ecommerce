# Predicción inteligente de gasto en clientes e-commerce

Proyecto de aprendizaje automático supervisado enfocado en la **predicción del monto promedio de compra** de clientes de e-commerce a partir de variables demográficas y de comportamiento digital.

## Objetivo

Desarrollar un modelo de **regresión supervisada** capaz de estimar el monto promedio de compra de un cliente, aplicando un pipeline completo de machine learning que incluya:

- generación de datos sintéticos,
- análisis exploratorio,
- limpieza y preprocesamiento,
- validación cruzada,
- entrenamiento y comparación de modelos,
- optimización de hiperparámetros,
- interpretación de resultados,
- selección del modelo final.

## Contenido del proyecto

El notebook incluye:

- generación de un dataset sintético de clientes e-commerce,
- tratamiento de valores nulos y outliers,
- codificación de variables categóricas,
- escalado de variables numéricas,
- división en entrenamiento y prueba,
- validación cruzada,
- entrenamiento de modelos de regresión:
  - Regresión Lineal
  - Regresión Polinomial
  - Ridge
  - Lasso
  - Gradient Boosting Regressor
- comparación mediante métricas:
  - MAE
  - MSE
  - RMSE
  - R²
- optimización con `GridSearchCV`,
- análisis de desempeño y selección del modelo final.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Estructura del repositorio

```bash
.
├── Predicción_inteligente.ipynb
├── README.md
├── .gitignore
└── requirements.txt
