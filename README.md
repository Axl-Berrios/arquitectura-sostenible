# arquitectura-sostenible

# Análisis de Métricas de Sustentabilidad en Proyectos de Arquitectura

Este proyecto se centra en el análisis de métricas clave relacionadas con la sustentabilidad, eficiencia energética, y diseño en proyectos de arquitectura. Se utiliza un conjunto de datos simulado que incluye información sobre consumo de energía, flujo de personas, costos de construcción, tiempo de construcción, impacto ambiental, y otros factores relevantes.

## Contenido

- **Generación de Datos**: Se crea un DataFrame con datos simulados para los años 2019 a 2024.
- **Análisis de Datos**: Se realizan diversos análisis para evaluar la eficiencia energética, el flujo de personas, los costos de construcción, la resiliencia, y la sustentabilidad.
- **Visualización de Datos**: Se utilizan bibliotecas como Matplotlib, Seaborn y Plotly para crear gráficos que muestran tendencias y correlaciones entre las métricas.
- **Modelo Predictivo**: Se desarrolla un modelo de regresión lineal y se optimiza con Random Forest para predecir la sustentabilidad basada en otras métricas.

## Análisis Realizados

1. **Eficiencia Energética**: Evaluación del consumo de energía promedio por año.
2. **Flujo de Personas y Optimización de Espacios**: Análisis de la correlación entre el flujo de personas y la optimización de espacios.
3. **Costos y Tiempos de Construcción**: Cálculo de promedios y tendencias de costos y tiempos de construcción.
4. **Simulación de Resiliencia**: Análisis de la probabilidad de fallos en la resiliencia de los proyectos.
5. **Diseño Climático**: Evaluación de la adecuación de los diseños al clima.
6. **Tendencias en Diseño**: Análisis de las preferencias del usuario en diseño.
7. **Sustentabilidad**: Cálculo de un índice de sustentabilidad basado en múltiples factores.
8. **Accesibilidad e Inclusión**: Evaluación de la conformidad con estándares de accesibilidad.
9. **Visualización Avanzada**: Creación de gráficos interactivos y dashboards para la visualización de métricas clave.

## Resultados

- **Promedios y Tendencias**: Identificación de patrones en eficiencia energética, sustentabilidad y accesibilidad.
- **Relaciones**: Correlaciones entre optimización de espacios, flujo de personas, y otras métricas clave.
- **Distribuciones**: Gráficos que muestran la dispersión y tendencias en resiliencia, accesibilidad y diseño climático.
- **Modelo Predictivo**: Se desarrolló un modelo de regresión lineal y se optimizó con Random Forest, logrando un R² de 0.888.

## Recomendaciones

Se generaron recomendaciones específicas para proyectos con bajo desempeño en métricas clave, sugiriendo mejoras en diseño climático y estrategias de mitigación de riesgos.

## Instalación

Para ejecutar este proyecto, asegúrate de tener instaladas las siguientes bibliotecas de Python:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter-dash
