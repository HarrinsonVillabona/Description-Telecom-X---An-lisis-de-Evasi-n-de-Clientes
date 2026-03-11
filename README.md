# 📡 Telecom X: Análisis de Churn de Clientes

Este proyecto forma parte de una iniciativa estratégica de **Telecom X** para reducir la tasa de evasión (churn). Utilizando técnicas de **Data Science**, el objetivo es identificar patrones de comportamiento en los clientes que deciden cancelar el servicio y proporcionar recomendaciones basadas en datos para mejorar la retención.

##  Objetivo del Proyecto
Analizar un conjunto de datos de clientes para extraer información valiosa (insights) mediante un proceso completo de **ETL** y un **Análisis Exploratorio de Datos (EDA)**.

##  Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Entorno:** Google Colab / Jupyter Notebook
* **Librerías principales:**
    * `Pandas`: Manipulación y limpieza de datos.
    * `Matplotlib` & `Seaborn`: Visualización de datos estratégica.
    * `Requests` & `JSON`: Extracción de datos desde APIs.

## Estructura del Análisis
1. **Extracción:** Carga de datos desde archivos JSON y normalización de estructuras anidadas.
2. **Transformación (ETL):** * Tratamiento de valores nulos y conversión de tipos de datos.
    * Creación de nuevas métricas como `Cuentas_Diarias`.
    * Estandarización de variables a formato binario (1 y 0).
3. **Análisis Exploratorio (EDA):**
    * Análisis descriptivo de variables numéricas.
    * Visualización de la distribución de churn.
    * Relación entre variables categóricas (contratos, métodos de pago) y la evasión.
4. **Informe de Resultados:** Resumen de hallazgos y recomendaciones estratégicas.

##  Key Insights
* **Punto de Riesgo:** Los clientes son más propensos a irse durante los primeros **12 meses** de contrato.
* **Tipo de Contrato:** Los contratos "Mes a mes" presentan la tasa de evasión más alta.
* **Factor Económico:** Cargos mensuales elevados están correlacionados con una mayor probabilidad de cancelación.

## Cómo usar este repositorio
1. Sube el archivo `TelecomX_Data.json` a tu entorno de ejecución.
2. Abre el notebook `TelecomX_LATAM.ipynb` en Google Colab o Jupyter.
3. Ejecuta las celdas en orden secuencial para reproducir el análisis.
