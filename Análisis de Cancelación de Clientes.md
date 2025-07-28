# 📌 Informe Final – Análisis de Cancelación de Clientes

## 🎯 Objetivo
El objetivo de este análisis fue identificar los factores más relevantes que influyen en la cancelación de clientes (churn) y proponer estrategias de retención basadas en los resultados obtenidos a través de distintos modelos de machine learning.

---

## 📊 Factores Principales Identificados

Con base en el análisis de la importancia de las variables, se identificaron los siguientes factores como los más influyentes en la cancelación:

- **Tiempo de permanencia del cliente**: Los clientes con menos meses en la compañía tienden a cancelar más frecuentemente.
- **Soporte técnico deficiente**: Un número elevado de tickets o llamadas al servicio técnico se relaciona con la cancelación.
- **Uso bajo del servicio**: Clientes que utilizan poco el servicio presentan una mayor probabilidad de cancelación.
- **Facturación elevada o cargos extra**: La presencia de cargos adicionales o facturas altas incrementa la tasa de cancelación.
- **Tipo de contrato**: Contratos mensuales tienen mayor tasa de churn comparado con los contratos anuales.

---

## 📈 Análisis del Desempeño de los Modelos

Los modelos fueron evaluados utilizando métricas como precisión, recall, F1-score y matriz de confusión. Se identificó que:

- El modelo **Random Forest** obtuvo el mejor rendimiento general, con una buena capacidad para identificar tanto a clientes que permanecen como a los que cancelan.
- El modelo **KNN** mostró señales de **overfitting**, ya que tuvo un alto desempeño en entrenamiento pero bajo en prueba.
- La **Regresión Logística** ofreció interpretabilidad aceptable, permitiendo entender claramente la relación entre variables y churn.

---

## 🛡️ Estrategias de Retención Recomendadas

Basado en los factores encontrados, se proponen las siguientes estrategias para reducir la cancelación de clientes:

- **Programas de fidelización para nuevos clientes**: Ofrecer incentivos especiales durante los primeros meses del servicio.
- **Mejora del soporte técnico**: Reducir los tiempos de respuesta y aumentar la satisfacción en la resolución de problemas.
- **Alertas y seguimiento por bajo uso**: Notificar al cliente sobre su bajo uso e incentivarlo con recomendaciones personalizadas.
- **Revisión y ajuste de tarifas**: Transparencia en la facturación y beneficios para usuarios con cargos adicionales.
- **Fomentar contratos de mayor duración**: Ofrecer descuentos u ofertas exclusivas para clientes con contratos anuales.

---

## ✅ Conclusión

El análisis permitió identificar variables clave en la cancelación de clientes y ofrecer recomendaciones prácticas basadas en datos. Implementar estas estrategias puede mejorar significativamente la retención y satisfacción del cliente.

