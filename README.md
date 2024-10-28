# Análisis de Modelos

## Descripción del Proyecto

Este proyecto se centra en la implementación y evaluación de diferentes modelos de machine learning aplicados a conjuntos de datos específicos. El objetivo es analizar la efectividad de cada modelo en la predicción y clasificación, así como interpretar los resultados obtenidos.

### Conjuntos de Datos

1. **Precios de Automóviles**: Un conjunto de datos que incluye características de automóviles y sus precios de venta.
2. **Condición Cardíaca de Pacientes**: Datos sobre pacientes para clasificar la presencia de condiciones cardíacas.
3. **Calidad del Vino**: Un conjunto de datos que contiene propiedades químicas de diferentes vinos y su calidad.

---

## Modelos Utilizados

### 1. Regresión Lineal

- **Descripción**: Predice los precios de venta de automóviles basándose en características como el tipo de combustible y la transmisión.
- **R²**: 0.728
- **MSE**: 6.264
- **Análisis**: Aunque el modelo explica el 72.8% de la variabilidad en los precios, existe un 27.2% que queda sin explicar, sugiriendo que se podrían incluir más variables para mejorar el modelo.

### 2. Regresión Logística

- **Descripción**: Clasifica la condición cardíaca de los pacientes.
- **Exactitud**: 88.89%
- **Precisión**: 94.44%
- **Sensibilidad**: 80.95%
- **F1-score**: 87.18%
- **Análisis**: El modelo tiene una buena precisión, pero presenta un número significativo de falsos negativos, lo que sugiere que no está identificando todos los pacientes con la condición.

### 3. Árbol de Decisión

- **Descripción**: Predice la calidad del vino basado en propiedades químicas.
- **Precisión máxima**: 68.1% al incluir todas las características.
- **Análisis**: La precisión del modelo mejoró significativamente con la inclusión de características adicionales. Se identificaron umbrales críticos que afectan la calidad del vino, mostrando la utilidad del modelo en la predicción.

---

## Resultados y Análisis

Cada modelo presenta un rendimiento único y puede ser evaluado en función de su contexto de uso:

- **Regresión Lineal**: Proporciona predicciones razonables, pero podría mejorarse con variables adicionales.
- **Regresión Logística**: Muy preciso en la identificación de casos positivos, pero con margen para mejorar la sensibilidad.
- **Árbol de Decisión**: Eficaz para predecir calidad de vino, mostrando un incremento de precisión con más variables.

---

## Conclusiones

Cada modelo tiene sus propias fortalezas y debilidades. La elección del modelo debe basarse en los objetivos específicos del análisis y el contexto en el que se aplicará.

---

## Requisitos

Para ejecutar los modelos, asegúrate de tener instalados los siguientes requisitos:

- **Python 3.x**
- **Librerías necesarias**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Puedes instalar las librerías necesarias utilizando:

```bash
pip install -r requirements.txt

