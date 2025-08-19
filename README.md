# Challenge-TelecomX-parte-2 🛰️ Desafío 3 

📊 Predicción de Cancelación de Clientes

📌 Acerca del Proyecto

Este repositorio contiene un análisis predictivo enfocado en detectar qué factores influyen en la cancelación de clientes dentro de una empresa de telecomunicaciones. A través de técnicas de machine learning, se desarrollaron modelos capaces de anticipar el riesgo de abandono, permitiendo así diseñar acciones concretas para mejorar la retención.


🚀 ¿Cómo ejecutar el proyecto?

Puedes correr este análisis directamente en Google Colab, sin necesidad de instalar nada en tu computadora. Solo sigue estos pasos:

Abre el notebook en Colab haciendo clic aquí: 👉 Abrir en Google Colab

Una vez abierto, selecciona Archivo > Guardar una copia en Drive para trabajar sobre tu propia versión.

Ejecuta las celdas en orden para ver el análisis completo, gráficos y conclusiones.


⚙️ Modelos Implementados

Se trabajó con dos algoritmos de clasificación supervisada:

🌳 Árbol de Decisión

Precisión: 80%
Modelo robusto, fácil de interpretar y sin necesidad de normalizar los datos. Ideal para extraer reglas claras de negocio.

👥 K-Nearest Neighbors (KNN)

Precisión: 80%

Buen desempeño en la detección de cancelaciones (recall = 0.86), aunque más sensible a la escala de los datos y menos explicativo.

🔎 Modelo seleccionado: Árbol de Decisión, por su equilibrio entre métricas, facilidad de interpretación y aplicabilidad práctica.

🔍 Variables Clave en la Predicción

Durante el análisis, se identificaron las siguientes variables como las más influyentes en la probabilidad de cancelación:

⏳ Meses antigüedad: Clientes con menor antigüedad mostraron mayor propensión a cancelar.
💸 Cargos Mensuales: Tarifas mensuales elevadas se asociaron con mayor churn.
📄 Contrato: Los contratos "mes a mes" fueron los más vinculados a cancelaciones.
💳 Método de Pago: El uso de "Electronic Check" se relacionó con una mayor tasa de abandono.
🌐 Servicio Internet: Algunos tipos de conexión, como fibra óptica, mostraron correlación con cancelaciones.
🛠️ Soporte Tecnico: La falta de soporte técnico fue un factor de riesgo importante.

-

🧪 Técnicas Aplicadas

⚖️ SMOTE para balancear las clases y mejorar la detección de la clase minoritaria.

📈 Evaluación de modelos con métricas como accuracy, precision, recall y f1-score.

📊 Análisis exploratorio para entender la distribución y relación entre variables.

*💡 Propuestas de Retención*

Con base en los resultados obtenidos, se plantearon las siguientes acciones para reducir la tasa de cancelación:

🔒 Incentivar contratos a largo plazo mediante beneficios exclusivos.

👋 Acompañamiento a nuevos clientes durante los primeros meses con encuestas y soporte personalizado.

💰 Promover métodos de pago automáticos con recompensas o descuentos.

🧑‍💻 Mejorar el soporte técnico y monitorear la calidad del servicio de internet.

🧠 Implementar monitoreo predictivo con el modelo de Árbol de Decisión para actuar antes de que ocurra la cancelación.

**📂 Estructura del Repositorio**

📁 data/                  # Datos utilizados para el análisis
📁 notebooks/             # Notebook principal del proyecto
📁 models/                # Modelos entrenados y guardados
📄 README.md              # Este archivo
