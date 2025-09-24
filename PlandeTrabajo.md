# Plan de Trabajo:
## 1. Comprender el problema
- Objetivo del sprint: Predecir la cancelación de clientes.
- Importante saber que acciones preventivas puede hacer el área de marketing.

## 2. Revisión de los datos (EDA)
- Archivos: contract.csv, personal.csv, internet.csv, phone.csv en Carpera Final_provider2
- Revisar:
  - Filas, columnas, tipos de datos
  - Valores nulos y duplicados
  - Estadísticas básicas y visualizaciones

## 3. Preprocesamiento
- Unir datasets usando los customerID para tener la información
- Manejo de valores faltantes
- Transformación de variables categóricas
- Si aplica creación de nuevas variables

## 4. Análisis exploratorio y Modelado
- nalizar correlaciones entre variables y cancelación de clientes.
- Visualizaciones:
- Histogramas, boxplots, heatmaps de correlación.
- Gráficos de churn vs tipo de contrato, servicios, pagos.
- Identificar patrones o señales que indiquen riesgo de cancelación
- Probar modelos: Logistic Regression, Random Forest, XGBoost
- Métricas: Accuracy, F1-score, ROC-AUC

## 5. Evaluación final
- Evaluar modelo
- Brindar conclusiones con datos