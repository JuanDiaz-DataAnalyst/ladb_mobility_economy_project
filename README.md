# LADB Urban Mobility & Economic Analysis | Python

**English summary.** Analysis for the Latin American Development Bank (LADB) on whether urban mobility relates to economic productivity across cities. I combined TomTom Traffic Index data with OECD city indicators (GDP per capita, unemployment, population), filtered to 2024, built city-level mobility indicators, merged both sources and explored the relationship visually. Mexico City showed the highest average congestion, while GDP per capita varied widely without a consistent link to traffic delays.

- **Tools:** Python, Pandas, NumPy, Seaborn, Matplotlib (Jupyter Notebook)
- **Full case study:** [Notion portfolio](https://valuable-holly-5b4.notion.site/3a56df793f628047bfa0ea8b1d256b41)
- **Context:** project completed as part of the TripleTen Data Analytics Bootcamp.

---

## Resumen en español

Proyecto del programa de Analista de Datos de TripleTen. Este proyecto simula el trabajo de un analista de datos en el Latin American Development Bank (LADB), cuyo equipo debe entender cómo la movilidad urbana se relaciona con la productividad económica en distintas ciudades del mundo, con el fin de identificar en qué ciudades conviene invertir en infraestructura de transporte.

## Descripción del proyecto

El análisis combina dos fuentes reales de datos: movilidad urbana a través del TomTom Traffic Index (congestión, retrasos y tiempos de viaje en tiempo real) y economía urbana a través de OECD Cities (PIB per cápita, desempleo, población y contaminación). El trabajo busca responder qué ciudades presentan alta congestión y baja productividad económica, cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte), y qué variables parecen tener una relación más fuerte con el desarrollo urbano.

## Contenido del repositorio

El archivo `S5 ladb_mobility_economy_project_student.ipynb` es el notebook principal del proyecto. Contiene la limpieza y estandarización de ambas fuentes, el filtrado del año 2024, el cálculo de indicadores agregados por ciudad, la unión de los dos datasets, el análisis exploratorio con visualizaciones y las conclusiones finales.

## Fuentes de datos

`tomtom_traffic.csv` contiene registros de tráfico y congestión por ciudad, provenientes del TomTom Traffic Index. `oecd_city_economy.csv` contiene indicadores económicos y ambientales anuales por ciudad, recopilados por la OECD.

## Cómo abrir el notebook en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JuanDiaz-DataAnalyst/ladb_mobility_economy_project/blob/main/S5%20ladb_mobility_economy_project_student.ipynb)

También puedes abrirlo manualmente: entra al archivo `.ipynb` dentro de este repositorio y haz clic en el botón "Open in Colab".

## Cómo reproducir el análisis

Abre `S5 ladb_mobility_economy_project_student.ipynb` y ejecuta las celdas en orden: carga de datos, limpieza, filtrado por el año 2024, agregación por ciudad, unión de los datasets y visualizaciones. Si el notebook no incluye los datasets de forma automática, descarga `tomtom_traffic.csv` y `oecd_city_economy.csv` y cárgalos en el mismo entorno antes de ejecutar.

## Objetivo del análisis

Construir un dataset único, limpio y estandarizado a partir de dos fuentes distintas, enfocado en el año 2024. Calcular indicadores agregados de movilidad por ciudad y explorar visualmente la relación entre congestión vehicular y productividad económica, con el fin de generar hallazgos que apoyen decisiones de inversión en infraestructura de transporte por parte del banco.

## Herramientas utilizadas

Python (pandas, numpy, seaborn, matplotlib) en Jupyter Notebook.
