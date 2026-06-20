# Titirit-
It will work as a group project to develop for 3 months

#instructions 

Analizador Masivo de Clima e Histórico de Contaminación Ambiental
Origen de Datos (API/Archivo Gratuito): API pública de OpenWeatherMap (capa gratuita de
60 llamadas por minuto) combinado con un dataset histórico de contaminación en formato
CSV descargado gratis de Kaggle (de más de 500 MB).
Cómo funciona sin BD: Los alumnos descargarán el archivo CSV masivo a su entorno. El
programa de Python procesará el archivo plano directamente en memoria.
Integración:
➔ CAR: Dividir el CSV de millones de filas en "pedazos" (chunks) y usar multiprocessing
para calcular promedios de contaminación por ciudad de forma paralela en
segundos.
➔ SEN: Desplegar un script en la nube mediante Streamlit Cloud que consulte en
tiempo real la API de clima actual.
➔ VDB: Un dashboard en Streamlit que muestre mapas interactivos y KPIs del clima
actual versus las tendencias históricas del CSV.
