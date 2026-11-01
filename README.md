# Juegos de Steam: Clustering con K-Means

Análisis no supervisado del catálogo de Steam para agrupar los juegos según su desempeño (owners, reseñas, tiempo de juego, jugadores simultáneos, precio, etc.).

## Curso
Herramientas para Inteligencia Artificial

## Estructura del notebook (`steam_games.ipynb`)

1. Descarga del dataset con `kagglehub`.
2. Lectura de datos con Pandas (solo las columnas necesarias).
3. Preparación: Número de owners, filtro de juegos con datos confiables, outliers, escala logarítmica y estandarización.
4. Histogramas con Bokeh.
5. Elbow method para elegir el número de clusters.
6. K-Means con 3 clusters.
7. Gráficos de dispersión de los grupos.
8. Estadísticas y juegos más populares de cada grupo.
9. Clasificación de un juego nuevo.
