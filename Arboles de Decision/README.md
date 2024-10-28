# Árbol de Decisión

## Descripción

El modelo de árbol de decisión se aplica al conjunto de datos de calidad del vino, prediciendo la calidad en función de diversas características químicas.

## Métricas

- **Precisión máxima alcanzada**: 68.1% (al incluir todas las características)

## Análisis de Resultados

La inclusión progresiva de características mejora la precisión predictiva del modelo. Con solo la acidez fija como predictor, la precisión inicial fue del 40.0%. A medida que se añadieron variables como acidez volátil y ácido cítrico, la precisión aumentó a 53.1%, y con más variables, alcanzó un máximo del 68.1%.

El análisis de las características más relevantes muestra que el contenido de alcohol, los niveles de acidez y la presencia de sulfitos libres fueron clave para la precisión del modelo. Además, se identificaron umbrales críticos: niveles de alcohol superiores a 10.5 y bajos valores de acidez volátil (alrededor de 0.39 o menores) se asociaron con puntuaciones de calidad más altas.

## Conclusiones

El modelo de árbol de decisión se muestra como una herramienta eficaz para predecir la calidad del vino basándose en propiedades químicas esenciales. La identificación de umbrales críticos y la mejora progresiva en precisión con la inclusión de variables subrayan su utilidad en este contexto.

