# Análisis de uso de clientes – ConnectaTel

Análisis del uso de llamadas y mensajes de los clientes de ConnectaTel (México y Colombia) para encontrar patrones, detectar valores atípicos y crear segmentos de clientes que ayuden a mejorar la oferta de planes.

## Datasets
- `plans.csv`: planes disponibles (precio, minutos, GB y mensajes incluidos).
- `users_latam.csv`: clientes (edad, ciudad, fecha de registro, plan, churn).
- `usage.csv`: uso real (llamadas con duración y mensajes con longitud).

## Etapas del análisis
1. Carga y exploración de los datasets.
2. Identificación de problemas de calidad (nulos, sentinels y fechas fuera de rango).
3. Limpieza de datos.
4. Resumen estadístico del uso por usuario.
5. Histogramas, boxplots y detección de outliers.
6. Segmentación por nivel de uso y por edad.
7. Insights y recomendaciones para el negocio.

## Resultados clave
- El uso es bajo y similar entre los planes Básico y Premium.
- Cerca del 74% de los clientes tiene uso medio; solo cerca del 7% tiene alto uso.
- Los outliers (1% a 3% de los clientes) son usos altos pero posibles, por lo que se mantuvieron.

## Cómo ejecutar
1. Coloca `plans.csv`, `users_latam.csv` y `usage.csv` en la carpeta `/datasets/`.
2. Instala las librerías: `pip install pandas numpy seaborn matplotlib jupyter`.
3. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb` en Jupyter o Google Colab y ejecuta todas las celdas.
