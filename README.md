# Telecom-analysis - Sprint7-final-project
# Objetivo del proyecto

El objetivo de este proyecto es analizar los datos de clientes y uso de ConnectaTel para identificar patrones de comportamiento, detectar valores atípicos y comprender qué segmentos muestran necesidades diferenciadas. Para ello se trabajó con tres datasets: users, usage y plans, que contienen información de usuarios, registros de llamadas y mensajes, y tipos de planes de las regiones de México y Colombia. Los hallazgos buscan optimizar la oferta comercial y mejorar la experiencia del usuario

## 📂 Datasets utilizados

Para este análisis se utilizaron tres fuentes de información relacionadas con el servicio de telecomunicaciones de ConnectaTel:

1. plans.csv — contiene los planes disponibles actualmente, incluyendo precio, minutos incluidos, GB incluidos y costo por consumo adicional.
2. users_latam.csv — contiene información de los clientes de México y Colombia: edad, ciudad, fecha de registro y plan contratado.
3. usage.csv — contiene el detalle del uso real por usuario: llamadas con su duración en minutos y mensajes con su longitud en caracteres.

## ▶ Etapas del análisis realizadas

El análisis del proyecto se llevó a cabo a través de las siguientes etapas:

1. Carga y exploración de los datos: revisión inicial de la estructura, tipos de datos y primeras observaciones de cada dataset.
2. Identificación de problemas de calidad: detección de valores nulos, sentinels, fechas inválidas y valores atípicos.
3. Limpieza de datos: tratamiento de sentinels, imputación de nulos y estandarización de columnas.
4. Resumen estadístico: cálculo de medidas de tendencia central, dispersión y distribución por segmento.
5. Visualización y detección de outliers: histogramas, boxplots y análisis del rango intercuartílico (IQR).
6. Segmentación de clientes: clasificación de usuarios por grupo de edad y nivel de uso para identificar patrones de comportamiento.

## 🧠 Cómo ejecutar el notebook: 

# Opción 1 — Guardar directo desde Google Colab

Abre tu notebook en Colab
Ve a File → Save a copy in GitHub
Selecciona el repositorio y la carpeta correcta (ej: notebooks/)
Escribe un mensaje de commit claro, por ejemplo:

feat: add final ConnectaTel analysis
agregar version final: Análisis ConnectaTel


Verifica en GitHub que el archivo quedó en el lugar correcto

# Opción 2 — Subir manualmente desde GitHub

Descarga el notebook desde Jupyter: File → Download .ipynb
Entra a tu repositorio en GitHub
Haz clic en Add file → Upload files
Arrastra el archivo .ipynb y haz clic en Commit changes

## 📖 Breve guía de reproducción:

Clona el repositorio o abre el notebook directamente en Colab
Asegúrate de que los tres datasets estén disponibles en /datasets/:

plans.csv
users_latam.csv
usage.csv

Ejecuta todas las celdas en orden: Runtime → Run all
Los resultados, gráficas y segmentos se generarán automáticamente
