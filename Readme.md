# 📊 Challenge Telecom X – Análisis de Evasión de Clientes

## Descripción general del proyecto

Este proyecto se desarrolló como parte del desafío **"Challenge Telecom X"** de **Alura LATAM**, en el contexto del programa **Oracle Next Education (ONE)**. El objetivo central es abordar el problema de **evasión de clientes (_churn_)** en la empresa ficticia **Telecom X**, la cual pertenece al sector de telecomunicaciones. Asumiendo el rol de **analista de datos**, se realizó un estudio exhaustivo del comportamiento de los clientes para identificar patrones y causas asociadas a la cancelación de servicios.

Para ello, se llevó a cabo un proceso completo de **ETL (Extracción, Transformación y Carga)** de los datos obtenidos a través de una API en formato JSON. A continuación, se efectuó un **Análisis Exploratorio de Datos (EDA)**, incluyendo visualizaciones gráficas para detectar tendencias y relaciones significativas. Finalmente, se extrajeron **conclusiones e _insights_ clave** sobre los factores que contribuyen al churn, aportando información estratégica que servirá de base para que el equipo de ciencia de datos pueda desarrollar **modelos predictivos** enfocados en reducir la pérdida de clientes.

## 🎯 Objetivo

El objetivo de este proyecto es **analizar el comportamiento de los clientes** de Telecom X y **encontrar patrones** relacionados con la cancelación de sus servicios. Mediante la combinación de técnicas de ETL y un análisis exploratorio minucioso, se busca generar conocimiento accionable que ayude a **identificar las causas de la evasión**. Estos hallazgos permitirán proponer estrategias de retención de clientes y sentarán las bases para que, en un futuro, el equipo de ciencia de datos pueda **desarrollar modelos de predicción** sobre la propensión de un cliente a darse de baja.

## 🧰 Tecnologías utilizadas

- **Python 3** – Lenguaje principal para el desarrollo del análisis de datos  
- **Pandas** – Manipulación y análisis de datos estructurados  
- **NumPy** – Operaciones y cálculos numéricos de alto rendimiento  
- **Matplotlib** – Generación de gráficos y visualizaciones estáticas  
- **Seaborn** – Visualizaciones estadísticas más elaboradas y estéticas  
- **Jupyter Notebook** (Google Colab) – Entorno interactivo para ejecución del análisis  
- **Git & GitHub** – Control de versiones y alojamiento del proyecto  
- **API (JSON)** – Fuente original de los datos

## ⚙️ Estructura del repositorio

```bash
Challenge_Telecom/
├── TelecomX_LATAM.ipynb        # Notebook con el desarrollo completo
├── Data/
│   ├── TelecomX_Data.json      # Dataset en formato JSON
├── README.md                   # Archivo de documentación
```

## 💻 Instrucciones generales de uso

- Clona este repositorio o descárgalo como ZIP desde GitHub.
- Abre el archivo TelecomX_LATAM.ipynb en un entorno Jupyter Notebook o en Google Colab.
- Asegúrate de tener instaladas las dependencias necesarias: pandas, numpy, matplotlib, seaborn.
- Ejecuta las celdas en orden. El notebook cargará los datos, realizará la limpieza y generará los análisis.
- Revisa las conclusiones y visualizaciones al final del notebook para obtener los hallazgos del análisis.

💡 Nota: El archivo TelecomX_Data.json ya está incluido. Puedes modificar la ruta de carga si trabajas offline.

## 📦 Instalación

Si deseas ejecutar este proyecto en un entorno local, asegúrate de tener Python 3 instalado y luego ejecuta:

```bash
pip install pandas numpy matplotlib seaborn
```

## 🧪 Requisitos previos

- Python 3.7 o superior
- Entorno Jupyter Notebook o Google Colab
- Conexión a internet (si se desea cargar el dataset desde una URL externa)

## 📌 Estado del proyecto

Este proyecto se encuentra finalizado y fue entregado como parte del desafío Challenge Telecom X del programa Oracle Next Education - Alura LATAM.

## 🙏 Créditos y agradecimientos

Este proyecto fue desarrollado como parte del programa Oracle Next Education (ONE) en colaboración con Alura LATAM. Agradecemos a ambos por entregar este desafío práctico y valioso, que permitió poner en práctica conocimientos de análisis de datos, visualización y razonamiento estratégico.

## 📝 Licencia

Este proyecto fue desarrollado exclusivamente con fines educativos en el marco de un desafío formativo. No posee licencia comercial ni de uso profesional.