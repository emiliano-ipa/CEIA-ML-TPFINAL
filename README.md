# CEIA-ML-TP FINAL – Burnout en Empleados Corporativos

## 👥 Integrantes del Grupo

- **Martin Brocca** (<martinbrocca@gmail.com>)
- **Emiliano Iparraguirre** (<emiliano.iparraguirre22@gmail.com>)
- **Natalia Espector** (<nataliaespector@gmail.com>)
- **Agustin Lopez Fredes** (<agustin.lopezfredes@gmail.com>)
- **Fernando Martinez** (<fgmartinez1989@gmail.com>)

---

## 📄 Descripción del Proyecto

Este proyecto analiza un dataset relacionado con el *burnout* en empleados corporativos, disponible públicamente en el siguiente enlace:

> [Harvard Dataverse – Burnout Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VG6KQD)

El objetivo principal es explorar y modelar los factores asociados al desgaste laboral (*burnout*) a través de técnicas de análisis de datos, reducción de dimensionalidad y modelos de machine learning.

---

## 📂 Estructura del Repositorio

El repositorio contiene múltiples notebooks de Python organizados de la siguiente manera:

### Notebooks de preparación de datos:

#### [`TP1_EDA.ipynb`](./TP1_EDA.ipynb)
Análisis exploratorio de datos (EDA), que incluye:
- Limpieza e imputación de valores nulos
- Análisis de distribuciones
- Visualización de correlaciones y variables relevantes

#### [`TP1_PCA.ipynb`](./TP1_PCA.ipynb)
Aplicación de análisis de componentes principales (PCA) para:
- Reducción de dimensionalidad
- Evaluación de modelos sobre el dataset reducido
- Comparación de performance con respecto al dataset original

### Notebooks de modelos:
Para cada modelo realizado:
 - Explora el rendimiento de cada modelo con el dataset completo y el dataset reducido por PCA.
 - Detalla los reportes de clasificación y matrices de confusión para una comparación exhaustiva.
 - Evalúa el impacto de PCA en la precisión, exhaustividad y puntuación F1.
  
#### [`TP1_Models_KNN.ipynb`](./TP1_Models_KNN.ipynb)
Este notebook implementa y evalúa modelos K-Nearest Neighbors (KNN).


#### [`TP1_Models_SVM.ipynb`](./TP1_Models_SVM.ipynb)
Este notebook desarrolla y analiza modelos de Árboles de Decisión, Random Forest y Gradient Boosting.

#### [`TP1_Models_Trees.ipynb`](./TP1_Models_Trees.ipynb)
Este notebook desarrolla y analiza modelos de Árboles de Decisión, Random Forest y Gradient Boosting.

#### ['TP1_LogisticRegression.ipynb](./TP1_LogisticRegression.ipynb)
Este notebook desarrolla 4 modelos Regresión Logística Multiclase:
  - Dataset original
  - Dataset original con optimización de hiperparámetros
  - Dataset con Random Under Sampling
  - Dataset PCA 6 componentes
  
#### ['TP1_Models_Ensable.ipynb'](./TP1_Models_Ensamble.ipynb)
Este notebook desarrolla modelos de ensamble


---

## 🚀 Requisitos

Este proyecto utiliza [Poetry](https://python-poetry.org/) para la gestión del entorno y dependencias. Para instalar las dependencias:

```bash
poetry install

