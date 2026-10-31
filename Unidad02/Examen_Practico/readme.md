# Descripción del archivo `diabetes_prediction_dataset.csv`

## 1. Descripción general

El archivo `diabetes_prediction_dataset.csv` es un conjunto de datos diseñado para analizar factores relacionados con la diabetes y desarrollar modelos de aprendizaje automático (Machine Learning) que permitan predecir si una persona presenta esta enfermedad.

Contiene información demográfica, antecedentes de salud y mediciones clínicas de 100,000 personas, organizadas en 9 variables.

## 2. Descripción de las variables

| Variable              | Descripción                                                                            | Tipo de dato |
| --------------------- | -------------------------------------------------------------------------------------- | ------------ |
| `gender`              | Género de la persona: femenino, masculino u otro.                                      | Categórica   |
| `age`                 | Edad de la persona en años.                                                            | Numérica     |
| `hypertension`        | Indica si la persona tiene hipertensión (1 = sí, 0 = no).                              | Binaria      |
| `heart_disease`       | Indica si la persona tiene una enfermedad cardíaca (1 = sí, 0 = no).                   | Binaria      |
| `smoking_history`     | Antecedentes de tabaquismo: nunca, actual, anterior, entre otras categorías.           | Categórica   |
| `bmi`                 | Índice de masa corporal (IMC).                                                         | Numérica     |
| `HbA1c_level`         | Nivel de hemoglobina glucosilada (HbA1c), indicador del promedio de glucosa en sangre. | Numérica     |
| `blood_glucose_level` | Nivel de glucosa en sangre.                                                            | Numérica     |
| `diabetes`            | Variable objetivo que indica si la persona tiene diabetes (1 = sí, 0 = no).            | Binaria      |

## 3. Características del conjunto de datos

- Número de registros: 100,000.
- Número de variables: 9.
- Formato: CSV.
- Valores faltantes: No se encontraron valores nulos.
- Variable objetivo: `diabetes`.
- Proporción de casos positivos: 8.5 % de los registros corresponden a personas con diabetes.

## 4. Uso del conjunto de datos

Este archivo puede utilizarse para:

- Analizar la relación entre factores de salud y la diabetes.
- Identificar variables asociadas con una mayor probabilidad de presentar diabetes.
- Entrenar y evaluar modelos de clasificación, como árboles de decisión, regresión logística y Random Forest.
- Practicar limpieza, exploración y visualización de datos.

Nota: Los resultados de los modelos desarrollados con este conjunto de datos son herramientas de análisis y no sustituyen un diagnóstico médico profesional.
