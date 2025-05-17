# TFM_Retail
Repositorio de TFM de Máster de data science
# 📦 Predicción de Demanda Semanal en Retail | TFM Data Science

Este proyecto es parte de mi Trabajo de Fin de Máster (TFM) en Data Science & AI. El objetivo es desarrollar una solución analítica que permita a una cadena de retail anticipar la demanda semanal de cada producto por tienda, optimizando el proceso de abastecimiento y reduciendo tanto el exceso como la falta de stock.

---

## 🎯 Objetivo del Proyecto

Construir un sistema de predicción que estime la demanda de productos en diferentes tiendas (Nueva York, Boston y Filadelfia), utilizando datos históricos de ventas, precios y calendario.

---

## 🧠 Enfoque

1. **Análisis Exploratorio de Datos (EDA):**
   - Detección de patrones de venta por ciudad.
   - Identificación de productos en declive o estacionales.
   - Comparación de precios entre regiones.

2. **Clustering:**
   - Agrupación de productos por comportamiento de ventas.
   - Agrupación de tiendas según sus dinámicas semanales.

3. **Modelado Predictivo:**
   - Forecasting de ventas semanales con XGBoost.
   - Ingeniería de features (lags, medias móviles, tendencia, calendario, precios).
   - Validación temporal (hold-out).

4. **Visualización:**
   - Dashboard en Power BI para análisis de negocio.
   - Gráficos en Python para interpretación de resultados.

---

## 📊 Resultados

- **RMSE final:** ~4.6 unidades.
- Predicciones precisas a nivel tienda-producto-semana.
- Soporte estratégico para abastecimiento y campañas personalizadas.

---

## 🛠️ Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
- Power BI

---

## 📁 Estructura del repositorio
