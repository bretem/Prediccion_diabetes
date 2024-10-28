# Prediccion_diabetes
Prediccion iteración: Diabetis e Hipertensión

Esta trabajo explora la interacción entre la diabetes y la hipertensión. Comprender sus factores de riesgo es fundamental para una prevención y un tratamiento eficaces. Analizaremos en profundidad cómo se interconectan estas dos afecciones y las implicaciones para la salud en general.

## Objetivo

Predecir si un paciente tiene un riesgo potencial de padecer diabetes o hipertensión, con el objetivo de prevenir futuros costes sanitarios y de salud.
Para lograr este objetivo, utilizaremos técnicas avanzadas de machine learning.
Evaluaremos el rendimiento del modelo utilizando métricas como la precisión, la matriz de confusión y el AUC-ROC, asegurando así su eficacia y fiabilidad.

## Adquisición de los datos

El conjunto de datos de predicción de la diabetes resume una gran cantidad de información médica y demográfica extraída de los registros de los pacientes, junto con su estado de diabetes clasificado como positivo o negativo. Esta rica reserva de información abarca atributos cruciales que incluyen edad, sexo, índice de masa corporal (IMC), hipertensión, enfermedades cardíacas, antecedentes de tabaquismo, nivel de HbA1c y nivel de glucosa en sangre.

## Metodología

En este Proyecto vamos a entrenar los modelos GB, XGB y LGBM, realizando una comparativa y seleccionando el de mejor resultado, para nuestra predicción.

## Resultados

De los tres modelos entrenados, el que arroja mejores resultados es LGBMClarifier, prediciendo con un 97,35% de nivel de confianza, si un paciente es propenso a tener diabetis o hipertensión.
En resumen, el modelo LightGBM tiene un rendimiento excelente en general, con una alta precisión y AUC.
