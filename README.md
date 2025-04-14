# 🧬 BioPredict
BioPredict es una herramienta desarrollada en Python con el objetivo de facilitar el análisis y la predicción de enfermedades óseas, específicamente cáncer de hueso, a partir de datos clínicos. Esta aplicación está diseñada tanto para profesionales de la salud como para investigadores que deseen explorar patrones relevantes en los datos de pacientes.

A través de una interfaz interactiva construida con Streamlit, BioPredict permite visualizar y analizar características médicas como:
- Presión arterial
- Frecuencia cardíaca
- Niveles de glucosa
- Oxígeno en sangre
- Edad del paciente
- Otros factores relacionados

Además, implementa un modelo de Regresión Logística de la biblioteca scikit-learn, que permite predecir si un paciente presenta o no cáncer de hueso. Esta predicción se apoya en:
- Entrenamiento supervisado con datos clasificados
- Métricas de evaluación como exactitud y reporte de clasificación
- Visualización de la distribución de las variables por clase
También incluye análisis exploratorio de datos (EDA) y visualizaciones interactivas con seaborn, matplotlib y plotly, permitiendo detectar correlaciones y comportamientos entre variables.
La aplicación tiene un enfoque educativo y práctico, orientado al desarrollo de sistemas de apoyo para la toma de decisiones médicas.
