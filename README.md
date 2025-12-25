<div align="center">

# Mas Ventas != Mas Ganancia
### El peligro del descuento excesivo

![Estado](https://img.shields.io/badge/Estado-Finalizado-success?style=for-the-badge)
![Herramienta](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Datos](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

<br>

![Vista Previa del Dashboard](dashboard.png)

</div>

---

## 📋 Contexto del proyecto

Este proyecto analiza las ventas de un retail global ("Superstore") para identificar por que, a pesar de tener un **alto volumen de ventas**, la rentabilidad en ciertas regiones es critica. 

**Objetivo:** Transformar datos crudos en insights accionables para detener la fuga de dinero y optimizar la estrategia de precios.

---

## 🔍 Hallazgos clave

### 1. Volumen vs. Valor
Se detecto que categorias como **Furniture** generan grandes ingresos, pero margenes de ganancia minimos o incluso negativos. Vender mucho no siempre significa ganar dinero.

![Furniture Analysis](furniture.png)

### 2. El Problema de Texas
A traves del analisis geoespacial, se identifico a **Texas** como el estado con mayores perdidas **(-25k)**. El problema no es general, es localizado.
* **Culpables:** Ventas de *Tables* y *Binders* en la region central.

![Texas Map](texas.png)

### 3. La Trampa del Descuento 📉
El analisis de dispersion revelo una correlacion matematica directa y peligrosa:

> **"Descuentos superiores al 20% destruyen sistematicamente la rentabilidad, independientemente del volumen de venta."**

![Scatter Plot](Descuento.png)

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso en el proyecto |
| :--- | :--- |
| **Microsoft Excel** | Auditoria inicial y comprension de la estructura del dataset (`.csv` / `.xlsx`). |
| **Power BI (Power Query)** | Limpieza de datos (ETL), correccion de tipos de datos y filtrado. |
| **Power BI (DAX)** | Creacion de medidas para *Profit Margin* y *Average Discount*. |
| **Data Storytelling** | Diseño de dashboard interactivo con enfoque en la toma de decisiones. |

---

## 🚀 Conclusion y Recomendacion

Para recuperar la rentabilidad inmediata, los datos sugieren una accion critica:

**Establecer una politica de tope maximo de descuento del 20% en productos de la categoria Furniture, especificamente en la region Central (Texas).**

---
<div align="center">
  
Hecho con datos del dataset "Sample Superstore" 📊
  
</div>
