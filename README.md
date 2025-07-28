# CHALLENGE-TELECOM-X-PART-2
Desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.
# 📞 Análisis de Cancelación de Clientes (Churn Analysis) – Telecom X

## 📌 Informe Final

Este proyecto analiza los principales factores que influyen en la **cancelación de clientes (churn)** en una empresa de telecomunicaciones. Utilizando técnicas de machine learning, se busca comprender el comportamiento del cliente, evaluar el desempeño de varios modelos predictivos y proponer estrategias que contribuyan a la **retención de usuarios**.

---

## 🎯 Objetivo

El objetivo principal de este análisis es identificar los factores más relevantes asociados a la cancelación de clientes y recomendar estrategias de retención basadas en los resultados obtenidos mediante distintos modelos de clasificación.

---

## 📊 Factores Principales Identificados

Según el análisis de importancia de variables, los siguientes factores fueron los más determinantes en la cancelación:

- 🕒 **Tiempo de permanencia**: Clientes con pocos meses de servicio tienden a cancelar más.
- 🔧 **Soporte técnico deficiente**: Muchas solicitudes de soporte se relacionan con mayor churn.
- 📉 **Uso bajo del servicio**: Bajo consumo de servicios es un predictor importante.
- 💰 **Facturación elevada o cargos extra**: Clientes con cargos adicionales muestran mayor tasa de cancelación.
- 📄 **Tipo de contrato**: Los contratos mensuales tienen mayor probabilidad de cancelación que los contratos anuales.

---

## 🧠 Modelos Evaluados

Se entrenaron y evaluaron distintos modelos para predecir el churn, usando métricas como **precisión, recall, F1-score** y **matriz de confusión**:

| Modelo              | Observaciones |
|---------------------|---------------|
| 🔍 **Random Forest**       | Mejor desempeño general, equilibrio entre precisión y recall. |
| 📉 **K-Nearest Neighbors** | Buen rendimiento en entrenamiento, pero sufrió overfitting en prueba. |
| 📈 **Regresión Logística** | Menor rendimiento, pero gran interpretabilidad para entender el impacto de las variables. |

---

## 🛡️ Estrategias de Retención Recomendadas

A partir del análisis, se proponen las siguientes acciones para reducir el churn:

- 🎁 **Fidelización temprana**: Incentivos durante los primeros meses para nuevos clientes.
- 🛠️ **Optimización del soporte técnico**: Mejores tiempos de respuesta y calidad del servicio.
- 📬 **Alertas por bajo uso**: Enviar recomendaciones o promociones a clientes inactivos.
- 💵 **Revisión de facturación**: Transparencia en cargos y beneficios ante cobros adicionales.
- 🧾 **Fomentar contratos largos**: Bonificaciones para quienes elijan contratos anuales.

---

## ✅ Conclusión

El análisis de datos permitió detectar patrones claves en la cancelación de clientes, evaluar el rendimiento de modelos predictivos y proponer estrategias realistas y accionables. Implementar estas recomendaciones puede mejorar la **retención de clientes y aumentar su satisfacción**.

---

## 🧰 Herramientas utilizadas

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Machine Learning (Random Forest, Logistic Regression, KNN)
- Google Colab / Jupyter Notebooks
- Data Preprocessing (SMOTE, Normalización, Limpieza)

---
