# 📊 Proyecto de Análisis de datos para el comercio 'Sol Repuestos Japoneses'🛠️

# 👤 Autor
Juana Zorzolo Rubio 

📊 Estudiante avanzada de Tecnicatura Universitaria en IA

✉️ Contacto: 
- juanazorzolo266@gmail.com
- solrepuestosjaponeses@gmail.com


## 📝 Descripción

Este proyecto realiza un análisis exploratorio y visualización de datos de ventas y stock del comercio Sol Repuestos (un negocio dedicado a la venta de repuestos automotores), 
con el objetivo de brindar información estratégica para la toma de decisiones comerciales. A partir de los datos disponibles sobre ventas y stock, 
se identifican productos de alta y baja rotación, piezas más vendidas, distribución de ventas por marca y temporalidad, 
así como productos con stock crítico o desbalance entre stock y ventas.

## 📂 Estructura del proyecto

 - datos_ventas_marzo_mayo.csv — Dataset con las ventas realizadas entre marzo y mayo, incluyendo fecha, marca, modelo, producto, cantidad, precio y total.
 - datos_stock.csv — Dataset con el stock actual de productos disponibles, con información de cantidad y precio unitario.
 - Código en Python para carga, procesamiento, análisis y visualización de datos.

## 🛠️ Tecnologías y librerías utilizadas 
- Python 3.10 🐍
- pandas 🐼
- matplotlib 📉
- seaborn 🌊

## 🔍 Descripción del análisis realizado

1. Análisis exploratorio
- Inspección inicial de datos y tipos 📋
- Conversión de columnas a formatos adecuados (fechas) 📅

2. Análisis de ventas
- Identificación de productos de alta y baja rotación por cantidad vendida 🚀🐢

- Determinación de las piezas más vendidas agrupadas por marca y modelo 🔧

- Análisis de la distribución de ventas por marca mediante gráfico circular 🍰

- Estudio de la variación temporal de las ventas por mes y por día de la semana, para detectar patrones de demanda 📆⏰

3. Análisis de stock
- Detección de productos con stock crítico (menos de 3 unidades) ⚠️📉

- Visualización de los productos con bajo inventario 📦

4. Rentabilidad de productos
- Cálculo de la ganancia estimada para cada producto 💰
(Precio Unitario Venta - Precio Unitario Stock) * Cantidad Vendida

- Identificación y visualización de los productos más rentables 🥇

5. Desbalance entre stock y ventas
- Detección de productos que no tienen ventas pero sí stock ❌🛒

- Detección de productos que tienen ventas pero no stock 🛒❌

- Visualización de ambos casos para facilitar acciones comerciales o de abastecimiento 🔍

## 🎯Resultados esperados

- Identificación clara de productos clave para reposición y promoción 🔑

- Visualizaciones que permitan detectar oportunidades de mejora en stock y ventas 📈

- Análisis temporal para optimizar campañas y asignación de recursos ⏳

- Información relevante para aumentar la rentabilidad mediante la gestión adecuada del inventario y las ventas 💼

