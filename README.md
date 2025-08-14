# Challenge_TelecomX2
Desafio 3 TelecomX Parte 2

Análisis Predictivo de Churn de Clientes en Telecomunicaciones
📌 Introducción
Este proyecto tiene como objetivo principal predecir la cancelación de clientes (Churn) en una empresa de telecomunicaciones. Para ello, se han utilizado técnicas de análisis de datos y modelos de Machine Learning para identificar los factores más influyentes que llevan a un cliente a abandonar el servicio.

💾 Metodología
La metodología del proyecto se basó en los siguientes pasos:

Preparación de Datos: Se realizó un preprocesamiento del archivo TelecomX_Parte2.ipynb, incluyendo la limpieza y la codificación de variables categóricas para su uso en los modelos.

Modelado: Se implementaron y evaluaron dos modelos de clasificación para la predicción de Churn:

Regresión Logística: Un modelo lineal que es sensible a la escala de los datos, por lo que se aplicó una normalización previa.

Árbol de Decisión: Un modelo no lineal que no requiere normalización y toma decisiones basadas en umbrales de las variables.

Evaluación: Se evaluó el desempeño de cada modelo utilizando métricas clave como Exactitud, Precisión, Recall, F1-score y la Matriz de Confusión.

Análisis de Variables: Se investigó la importancia de las variables para cada modelo, lo que permitió identificar los factores más relevantes que predicen la cancelación.

📊 Resultados y Conclusiones
Los modelos de clasificación mostraron un rendimiento que permitió identificar los principales impulsores del Churn. Los hallazgos más importantes son:

Variables más Relevantes: El tipo de contrato (especialmente los contratos mes a mes), el servicio de fibra óptica, los cargos mensuales altos y la ausencia de soporte técnico son los factores que más influyen en la decisión de un cliente de cancelar el servicio. La antigüedad del cliente (tenure) actúa como un factor protector.

Desempeño de los Modelos: Los resultados de las métricas de evaluación ayudaron a determinar qué modelo se ajusta mejor a los datos, proporcionando una base para un análisis más profundo y la toma de decisiones.

🚀 Estrategias de Retención Propuestas
Con base en los resultados del análisis, se proponen las siguientes estrategias para mejorar la retención de clientes:

Fidelización: Implementar programas de fidelización para clientes con contratos mes a mes para incentivarlos a pasar a contratos de mayor duración.

Mejora del Servicio: Investigar y abordar las causas de la alta tasa de Churn en los clientes de fibra óptica.

Revisión de Precios: Ofrecer planes de precios más flexibles o descuentos para los clientes con altos cargos mensuales.

Fortalecimiento del Soporte Técnico: Mejorar el soporte técnico, ya que es un factor crítico de satisfacción y retención.

🤝 Colaboración
Este documento es una base para futuros análisis y discusiones. Se invita a explorar otros modelos, ajustar hiperparámetros o profundizar en el análisis de las variables identificadas.
