### Este repositorio contiene un pipeline de procesamiento de datos utilizando PySpark, organizado en las capas Bronze, Silver y Gold siguiendo buenas prácticas de ingeniería de datos.


# 📌 Descripción del proyecto
Se construye un flujo de datos que procesa información de vuelos, aeronaves, aeropuertos y mantenimientos, con el objetivo de generar indicadores analíticos para la toma de decisiones.

# 🏗️ Arquitectura del pipeline

El pipeline se divide en tres capas:

🥉 Bronze
 - Ingesta de datos desde archivos CSV
 - Tipificación inicial
 - Agregación de columnas de auditoría

🥈 Silver
 - Limpieza de datos
 - Validación de calidad
 - Eliminación de duplicados
 - Estandarización de campos

🥇 Gold
 - Construcción de KPIs:
 - Puntualidad de vuelos
 - Costos de mantenimiento
 - Rutas más frecuentes
