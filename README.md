# **Sistema Inteligente para Detección de Fallos en Rodamientos**
Desarrollado por: 
- Felipe Idárraga Quintero
- Julian Felipe Gutierrez Ramirez
- Samuel Marulanda Salazar

## **Descripción del Proyecto**
Este proyecto presenta el desarrollo de un sistema inteligente para la detección automática de fallos en rodamientos de motores eléctricos, utilizando técnicas de Machine Learning y Deep Learning.

Se empleó el conjunto de datos CWRU (Case Western Reserve University Bearing Dataset), extrayendo características estadísticas a partir de señales de vibración.

El sistema fue entrenado y evaluado con tres modelos de clasificación:
- Máquina de Vectores de Soporte (SVC)
- Bosque Aleatorio (Random Forest - RF)
- Perceptrón Multicapa (MLP)

El proyecto incluye el flujo completo de:
- Preprocesamiento de datos
- Extracción de características
- Entrenamiento y validación de modelos
- Evaluación mediante métricas de desempeño
- Implementación de un dashboard interactivo

Además, se desarrolló una interfaz en Streamlit que permite a usuarios no técnicos realizar diagnósticos en tiempo real.

## **Estructura del Repositorio**
'''bash
├── FProyecto_Final_TAM.ipynb     # Desarrollo completo del modelo
├── Dashboard_PFTAM.ipynb         # Dashboard interactivo para probar los modelos
├── Proyecto_Final_TAM.pdf        # Documentación completa del proyecto
└── README.md
'''

## **1. FProyecto_Final_TAM.ipynb**
Contiene todo el proceso de desarrollo:
- Carga del dataset CWRU
- Análisis exploratorio
- Extracción de características estadísticas
- Entrenamiento de modelos (SVC, RF, MLP)
- Evaluación y comparación de resultados

## **2. Dashboard_PFTAM.ipynb**
Incluye la implementación del dashboard interactivo que permite:
- Cargar datos
- Seleccionar modelos
- Visualizar predicciones
- Realizar diagnósticos de fallos

## **3. Proyecto_Final_TAM.pdf**
Documento técnico con:
- Marco teórico
- Metodología
- Resultados
- Análisis y conclusiones

## **Tecnologias Utilizadas**
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Streamlit

## **Objetivo**
Desarrollar una herramienta inteligente que facilite la detección temprana de fallos en motores eléctricos, contribuyendo al mantenimiento predictivo y reduciendo costos operativos en entornos industriales.
