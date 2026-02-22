# 📂 Challenge TelecomX2-Latam: Predicción de Cancelación de Clientes (Churn) en Telecomunicaciones

## ✅ Descripción General
Este proyecto se centra en el análisis de cancelación de clientes (churn) en una empresa de telecomunicaciones. Se trabaja con un conjunto de datos que contiene información sobre clientes, sus características demográficas, servicios contratados, métodos de pago y comportamiento de uso. El propósito es aplicar técnicas de preprocesamiento de datos, balanceo de clases y modelos de machine learning para identificar los factores que más influyen en la decisión de un cliente de cancelar su servicio.

En esencia, se trata de un proyecto de predicción de churn que combina análisis estadístico, visualizaciones y modelos predictivos para apoyar la toma de decisiones estratégicas en la empresa.

## 🎯 **Objetivos del Análisis**
* **Preprocesamiento de datos:** Limpieza, codificación de variables categóricas, normalización y balanceo de clases.

* **Análisis exploratorio:** Visualización de distribuciones, correlaciones y patrones de comportamiento.

* **Modelado predictivo:** Entrenamiento de modelos (Regresión Logística, Random Forest, SVM) y comparación de métricas.

* **Interpretación de resultados:** Análisis de coeficientes e importancia de variables.

* **Estrategias de retención:** Recomendaciones prácticas para reducir la tasa de churn.

## ⚠️ **Problemas a Resolver**

* **Alta tasa de cancelación (26.5%):** Afecta ingresos y estabilidad.

* **Desbalance de clases:** Mayoría de clientes no cancelan, dificultando el entrenamiento de modelos.

* **Identificación de factores clave:** Necesidad de entender qué variables influyen más en la decisión de cancelar.

* **Limitaciones en la predicción:** Modelos con accuracy cercano al 80%, pero con recall bajo para clientes que sí cancelan.

* **Estrategias de retención poco claras:** La empresa requiere acciones basadas en datos para disminuir pérdidas.

## 📊 **Principales Hallazgos**

Factores que aumentan la probabilidad de cancelación

* InternetService_Fiber optic

* PaymentMethod_Electronic check

* PaperlessBilling

* SeniorCitizen

* Servicios de streaming (TV y películas)

* Cargos mensuales altos

Factores que reducen la probabilidad de cancelación

* Tenure (antigüedad)

* Contratos largos (1 año, 2 años)

* **Servicios adicionales:** TechSupport y OnlineSecurity

* Clientes con pareja o dependientes

## 📈 **Rendimiento de los Modelos**

* Ningún modelo supera el 0.80 de accuracy, lo que indica que la predicción de cancelación es un problema complejo y multifactorial. La regresión logística y el SVM destacan por su interpretabilidad, mientras que Random Forest aporta robustez y análisis de importancia.

## 🚀 **Estrategias de Retención Propuestas**

* **Incentivar contratos largos:** Migrar clientes de contratos mensuales a anuales/bianuales con beneficios.

* **Mejorar soporte y seguridad digital:** Incluir TechSupport y OnlineSecurity en planes básicos.

* **Gestión de precios:** Ofrecer descuentos o planes personalizados a clientes con cargos mensuales altos.

* **Optimizar métodos de pago:** Reducir problemas asociados a Electronic Check y PaperlessBilling.

* **Segmentación de adultos mayores:** Programas de fidelización y soporte especializado.

* **Monitoreo de clientes nuevos:** Programas de bienvenida y seguimiento en los primeros meses.

## 🛠️ **Tecnologías Utilizadas**

* **Lenguaje:** Python

* **Librerías de análisis:** Pandas, NumPy

* **Visualización:** Matplotlib, Seaborn, Plotly

* **Machine Learning:** Scikit-learn (Logistic Regression, Random Forest, SVM)

* **Balanceo de clases:** Imbalanced-learn (SMOTE)

* **Control de versiones:** GitHub

* **Herramienta de gestión de proyectos:** Trello

## 📂 **Estructura del Proyecto**

* **Datos:** Dataset original y transformado.

* **Notebooks:** Jupyter Notebooks en Colab donde se realiza la codificación y ejecución del proyecto.

* **Models:** Entrenamiento y evaluación de modelos.

* **Visualizaciones:** Gráficos y reportes generados.

* **README.md:** Documento explicativo del proyecto.

## 📑 **Flujo de Trabajo**

* Carga y exploración inicial del dataset

* **Preprocesamiento:** limpieza, codificación y normalización

* Balanceo de clases con SMOTE

* Entrenamiento de modelos (Logística, RF, SVM)

* Evaluación de métricas y comparación de rendimiento

* Análisis de importancia de variables

* Visualización de resultados

* Conclusiones y estrategias de retención

## 🎯 **Conclusión**

Este proyecto demuestra cómo el análisis de datos y el machine learning pueden ayudar a predecir la cancelación de clientes y diseñar estrategias de retención basadas en evidencia.
Aunque los modelos alcanzan un rendimiento moderado (~80% accuracy), la verdadera utilidad está en la interpretación de variables clave y la aplicación práctica de los hallazgos para mejorar la fidelización.

## 📌 **Autor**

Proyecto desarrollado como parte del Challenge TelecomX2 de la formación de Data Science + IA de Alura Latam.

Análisis y documentación elaborados por María Fernanda Hernández Solano.
