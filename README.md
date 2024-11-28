# Predicción del Rendimiento de Cultivos

Este proyecto utiliza técnicas de aprendizaje automático para predecir el rendimiento de cultivos agrícolas basándose en variables como el tipo de cultivo, altitud, área sembrada y cosechada, entre otras. El objetivo principal es apoyar la toma de decisiones en el sector agrícola mediante modelos precisos y herramientas analíticas.

---

## Características del Proyecto

- **Análisis Exploratorio de Datos (EDA):** Visualización y análisis detallado para identificar patrones y anomalías en los datos.
- **Tratamiento de Datos Faltantes:** Técnicas estadísticas para imputar valores faltantes.
- **Preprocesamiento de Datos:** Normalización y eliminación de variables poco relevantes para el modelo.
- **Manejo del Desbalance de Clases:** Implementación de sobremuestreo con `RandomOverSampler` para mejorar la representación de clases minoritarias.
- **Modelado:** Entrenamiento de modelos supervisados como Random Forest para la predicción de rendimiento.
- **Evaluación del Modelo:** Métricas como accuracy, precision, recall y F1-score para evaluar el rendimiento del modelo.

---

## Requisitos Previos

Asegúrate de tener instaladas las siguientes dependencias antes de ejecutar el proyecto:

- Python 3.8 o superior
- Bibliotecas necesarias: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `seaborn`
  - `matplotlib`
  - `imblearn`