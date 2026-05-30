# Estuidio-de-Aguacates-Monarca
🥑 Aguacates Monarca: Análisis y Predicción del Mercado Agrícola
Este repositorio contiene el código, los datos y la documentación del estudio de caso desarrollado para Aguacates Monarca, una PyME productora y comercializadora de aguacate con sede en Michoacán, México.

El proyecto se centra en la extracción, limpieza y análisis de datos gubernamentales y de mercado para generar modelos predictivos que optimicen la toma de decisiones estratégicas en producción, fijación de precios y gestión de riesgos climáticos.

🎯 Objetivos del Proyecto
Proyección de Producción: Estimar el volumen de producción de aguacate a nivel nacional y estatal (Michoacán).

Proyección de Precios (2026): Anticipar el comportamiento del precio del aguacate en el mercado para el año en curso.

Análisis de Riesgo Climático: Evaluar la probabilidad de precipitación en Michoacán a corto plazo para mitigar riesgos en las cosechas.

📊 Fuentes de Datos
Los conjuntos de datos utilizados en este estudio provienen de fuentes oficiales e institucionales:

SNIIM (Sistema Nacional de Información e Integración de Mercados): Datos históricos de precios y comercialización, con especial atención a la estandarización de variables como la "Presentación" (pesos y empaques).

SENASICA (Servicio Nacional de Sanidad, Inocuidad y Calidad Agroalimentaria): Registros fitosanitarios y de volumen de exportación/movilización.

Bases de Datos Climatológicas: Registros históricos de precipitación en el estado de Michoacán.

🧠 Modelos y Metodología
El análisis se divide en tres ejes principales, cada uno abordado con diferentes técnicas estadísticas y de Machine Learning:

Producción Agrícola (Regresión Polinomial): * Se implementó un modelo de regresión polinomial para capturar las tendencias no lineales en la producción histórica de aguacate, tanto a nivel nacional como específico para Michoacán.

Predicción de Precios (ARIMA): * Se entrenó un modelo autorregresivo integrado de media móvil (ARIMA) para predecir las fluctuaciones de precio del aguacate para el año 2026, considerando la estacionalidad y los ciclos de cosecha.

Pronóstico Climático (Cadenas de Markov): * Se desarrolló un modelo probabilístico basado en Cadenas de Markov para predecir la probabilidad de lluvia (estados: lluvia / no lluvia) en Michoacán durante los próximos 2 meses.

💻 Tecnologías Utilizadas
Lenguaje Principal: Python

Manipulación y Limpieza de Datos: Pandas, NumPy, PySpark

Modelado y Machine Learning: Scikit-learn, statsmodels (para ARIMA)

Visualización: Power BI, Matplotlib / Seaborn

Entorno: Jupyter Notebooks
