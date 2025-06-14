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

### [`TP1_EDA.ipynb`](./TP1_EDA.ipynb)
Análisis exploratorio de datos (EDA), que incluye:
- Limpieza e imputación de valores nulos
- Análisis de distribuciones
- Visualización de correlaciones y variables relevantes

### [`TP1_PCA.ipynb`](./TP1_PCA.ipynb)
Aplicación de análisis de componentes principales (PCA) para:
- Reducción de dimensionalidad
- Evaluación de modelos sobre el dataset reducido
- Comparación de performance con respecto al dataset original

---

## 🚀 Requisitos

Este proyecto utiliza [Poetry](https://python-poetry.org/) para la gestión del entorno y dependencias. Para instalar las dependencias:

```bash
poetry install
