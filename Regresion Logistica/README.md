# Regresión Logística

## Descripción

Este modelo se utiliza para clasificar la condición cardíaca de los pacientes, evaluando si un paciente tiene o no una condición cardíaca específica.

## Métricas

- **Exactitud**: 88.89%
- **Precisión**: 94.44%
- **Sensibilidad (Recall)**: 80.95%
- **F1-score**: 87.18%

## Análisis de Resultados

El modelo de regresión logística ha demostrado un rendimiento sólido con una exactitud del 88.89%. La precisión de 94.44% sugiere que la mayoría de las predicciones positivas realizadas son correctas. Sin embargo, la sensibilidad del modelo es del 80.95%, lo que implica que un porcentaje significativo de pacientes con la condición cardíaca no son identificados. 

La matriz de confusión revela que el modelo clasificó correctamente 48 de los 50 casos negativos y 40 de los 49 casos positivos, con 8 falsos negativos y 7 falsos positivos. Esto indica que el modelo es más efectivo en la identificación de pacientes sin la condición que en la detección de aquellos que sí la tienen.

## Conclusiones

Aunque el modelo muestra un buen equilibrio entre precisión y sensibilidad, hay un margen significativo para mejorar la identificación de todos los casos positivos, lo que es crítico para asegurar que los pacientes que necesitan atención médica sean detectados adecuadamente.
