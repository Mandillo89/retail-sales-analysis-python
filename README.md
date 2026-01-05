# 📊 Retail Sales Analysis (EDA) — Python

## 🧠 Overview
Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** sobre ventas retail con el objetivo de identificar patrones de consumo, desempeño por categoría de producto y comportamiento de clientes. El análisis está orientado a generar **insights accionables** que apoyen la toma de decisiones de negocio.

---

## 🎯 Business Objective
- Identificar categorías de producto con mayor y menor desempeño.
- Analizar tendencias de ventas a lo largo del tiempo.
- Evaluar el comportamiento de compra por segmentos demográficos (edad y género).
- Calcular KPIs clave como ingresos totales, ticket promedio y volumen de transacciones.

---

## 📦 Dataset
- **Fuente:** Dataset público de ventas retail (CSV)
- **Contenido principal:**
  - Fecha de transacción
  - Cliente
  - Categoría de producto
  - Cantidad
  - Precio por unidad
  - Monto total
  - Edad y género del cliente

> El dataset fue limpiado y estandarizado para el análisis (tipos de datos, fechas, duplicados y validaciones básicas).

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📂 Project Structure
retail-sales-analysis-python/
│── data/
│ └── raw/
│ └── retail_sales_dataset.csv
│── notebooks/
│ └── 01_eda_retail_sales.ipynb
│── images/
│ ├── sales_by_category.png
│ ├── monthly_sales.png
│ ├── sales_by_gender.png
│ └── sales_by_age_group.png
│── requirements.txt
│── README.md


---

## 📊 Key Analysis & KPIs
- **Total Revenue**
- **Average Ticket Size**
- **Average Quantity per Transaction**
- **Number of Transactions**
- **Unique Customers**

Análisis realizados:
- Ingresos por categoría de producto.
- Tendencia mensual de ventas.
- Segmentación por género.
- Segmentación por rangos de edad.
- Top clientes por ingresos.

---
## 💡 Key Insights
- Una categoría de producto concentra la mayor parte de los ingresos, lo que sugiere un mayor nivel de preferencia por parte de los clientes.
- Se identifican patrones de estacionalidad en las ventas mensuales, lo que puede apoyar la planeación comercial.
- Los segmentos de edad muestran diferencias claras en el comportamiento de compra.
- El ticket promedio sugiere oportunidades para estrategias de cross-selling y promociones.
- La segmentación demográfica puede ser utilizada para campañas más focalizadas.

---

## 📈 Business Recommendations
- Priorizar las categorías con mayor desempeño en estrategias comerciales y de inventario.
- Diseñar campañas promocionales enfocadas en los segmentos de clientes más rentables.
- Monitorear KPIs de manera periódica para detectar cambios en el comportamiento del consumidor.
- Profundizar el análisis incorporando datos de costos para evaluar rentabilidad.

---

## ▶️ How to Run
1. Clonar el repositorio.
2. Instalar dependencias:
   pip install -r requirements.txt
3. Ejecutar el notebook: notebooks/01_eda_retail_sales.ipynb

🚀 Next Steps

Integrar análisis por tienda o región (si se dispone de la información).

Incorporar modelos predictivos básicos para estimar demanda.

Crear dashboards interactivos en Power BI o Tableau.
