# Jupyter Notebooks para el TFG

Modelos de clasificación en cuadernos jupyter a presentar en el TFG:

1. Mejorar con el modelo de clasificación presentado en [Innate and Adaptive Immune Assessment at Admission to
Predict Clinical Outcome in COVID-19 Patients](https://pubmed.ncbi.nlm.nih.gov/34440121/)
  - Replicación del modelo de Regresión Logística evaluado con ROC AUC
  - Optimización búsqueda clasificador óptimo con [Autosklearn](https://automl.github.io/auto-sklearn/master/)
    - Selección atributos, imputación, normalización, técnicas de desequilibrado, ajuste de parámetros
  - Evaluación con múltiples medidas de evaluación comparando clasificadores con [Pipeline Profiler](https://towardsdatascience.com/exploring-auto-sklearn-models-with-pipelineprofiler-5b2c54136044/)
2. Preprocesado de datos de entrada para optimizar los modelos  Regresión vs Modelo óptimo 
  - Comparación de modelos para ajustar parámetros y preprocesado [Autosklearn](https://automl.github.io/auto-sklearn/master/)
    - Selección atributos, imputación, normalización, técnicas de desequilibrado, ajuste de parámetros  
  - Optimización de parámetros del clasificador con [Optuna](https://optuna.org/)
  - Explicación de atributos con más influencia en el modelo con [Shap](https://github.com/slundberg/shap) 



