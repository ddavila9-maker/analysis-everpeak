# EverPeak Analysis: Tráfico Urbano vs. Indicadores Económicos

Este es mi primer proyecto de análisis de datos, en el que exploro la relación entre la movilidad urbana y el desempeño económico de distintas ciudades durante 2024. Combino datos de congestión vehicular (TomTom) con indicadores económicos (OECD) para ver si existe algún patrón entre ambas variables.

## Objetivo

Investigar si hay una relación entre el tráfico de una ciudad (retrasos, congestión, tiempos de viaje) y su desempeño económico (PIB per cápita), usando datos reales del año 2024.

##  Fuentes de datos

- *`tomtom_traffic.csv`* - Datos de tráfico por ciudad: índice de congestión, minutos de retraso, longitud de embotellamientos, tiempos de viaje, entre otros.
- *`oecd_city_economy.csv`* - Indicadores económicos por ciudad, incluyendo PIB per cápita.

##  Proceso de análisis

El proyecto está estructurado en las siguientes etapas:

1. **Carga y exploración inicial** — Importo las librerías (`pandas`, `numpy`, `seaborn`, `matplotlib`) y cargo ambos datasets para conocer su estructura.
2. **Limpieza y preparación** — Reviso tipos de datos, valores nulos y nombres de columnas, y corrijo los formatos numéricos y de fecha que lo requieren.
3. **Filtrado por año** — Extraigo el año de cada registro y me quedo únicamente con los datos correspondientes a 2024.
4. **Resumen de movilidad** — Calculo promedios anuales por ciudad de las métricas de tráfico más relevantes (retrasos, congestión, tiempos de viaje, etc.).
5. **Unión de datasets** — Combino la información de tráfico y economía en un solo DataFrame, usando ciudad y año como claves de unión.
6. **Visualización** — Genero gráficos (boxplot, histograma y gráfico de barras comparativo) para observar la distribución de cada variable y explorar si existe alguna relación entre ellas.
7. **Documentación de resultados** — Exporto el dataset limpio y resumo mis hallazgos.

##  Tecnologías utilizadas

- Python
- pandas
- numpy
- seaborn
- matplotlib

##  Cómo ejecutar el proyecto

```bash
pip install pandas numpy seaborn matplotlib
jupyter notebook
```

Luego abre el notebook principal y ejecuta las celdas en orden.

##  Resultados

Los gráficos y el análisis muestran cómo se distribuyen el tráfico y el PIB per cápita entre las ciudades estudiadas, y permiten identificar si existe alguna tendencia entre congestión vehicular y desarrollo económico. *(Aquí puedes añadir tus conclusiones específicas una vez definidas.)*

##  Autor

Proyecto realizado por mí como parte de mi aprendizaje en análisis de datos con Python.
### 7.1 Guardar dataset final¶
Objetivo: Generar un CSV limpio, reproducible y con columnas relevantes para análisis posterior.



