
# 📡 Telecom X – Análisis y Predicción de Churn de Clientes

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1j2pD2sJUPThrUegTmsdX22Qiu9EFbOY3?usp=sharing)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/memo7499/challenge-telecom-x)
![Python](https://img.shields.io/badge/Python-3.12.12-blue?logo=python)
![Made with](https://img.shields.io/badge/Hecho%20con-Pandas%20|%20Matplotlib%20|%20Numpy%20|%20Seaborn-blue)

---

Proyecto de **Análisis Exploratorio de Datos (EDA)** y **modelo predictivo de churn** para Telecom X.  
El objetivo es comprender los factores que impulsan la evasión de clientes y construir un modelo interpretable que permita anticiparla y apoyar estrategias de retención.

---

## 📋 Tabla de contenidos
1. [📖 Descripción](#-Descripción)
2. [🎯 Objetivo](#-Objetivo)
3. [📊 Insights Principales](#️-Insights-principales)
4. [📊 Visualizaciones destacadas](#-Visualizaciones-destacadas)
5. [🤖 Modelo predictivo](#-Modelo-predictivo)
6. [💡 Recomendaciones estratégicas](#-Recomendaciones-estratégicas)
7. [🔮 Próximos pasos](#-Próximos-pasos)
8. [👤 Autor](#-Autor)

---

## 📖 Descripción

Telecom X enfrenta una **tasa de churn del 26.5%**, lo que representa un impacto relevante en ingresos y estabilidad de la base de clientes.  
Este proyecto analiza **7,267 registros de clientes**, aplicando un flujo completo de:
- ETL (Extracción, Transformación y Carga)
- Análisis Exploratorio de Datos (EDA)
- Modelado predictivo interpretable

El resultado es un conjunto de **insights accionables** y un modelo con buen desempeño predictivo.

---

## 🎯 Objetivo

- Identificar los factores clave asociados al churn  
- Analizar la sensibilidad al precio y al tipo de contrato  
- Construir un modelo predictivo interpretable  
- Generar recomendaciones estratégicas basadas en datos  

---

## 📊 Insights principales

- **26.5%** de los clientes abandonan el servicio.  
- El churn es mayor en clientes con **baja antigüedad (tenure)**.  
- Los contratos **mes a mes** concentran la mayor tasa de evasión.  
- Contratos de **1 y 2 años** reducen significativamente la probabilidad de churn.  
- Los clientes que churnean presentan **cargos mensuales más altos**.  
- **Fiber optic**, **paperless billing** y **electronic check** están asociados a mayor churn.  

> **Insight clave:** el churn no es aleatorio; responde a patrones claros de compromiso, precio y tipo de servicio.

---

## 📊 Visualizaciones destacadas

### Distribución del Churn
![Distribución del Churn](https://github.com/memo7499/challenge-telecom-x/blob/main/CHURN.png)

*El 26.5% de los clientes abandonan el servicio, lo que representa un impacto relevante para el negocio.*


### Churn por Tipo de Contrato
![Churn por Tipo de Contrato](https://github.com/memo7499/challenge-telecom-x/blob/main/CHURN_CONTRATO.png)

*Los contratos mes a mes presentan la mayor tasa de churn, mientras que los contratos de uno y dos años actúan como un fuerte factor de retención.*


### Churn por Servicio de Internet
![Churn por Servicio de Internet](https://github.com/memo7499/challenge-telecom-x/blob/main/CHURN_INTERNET.png)

*Los clientes con servicio de fibra óptica muestran una mayor propensión al churn, posiblemente asociada a mayores cargos mensuales.*


### Churn por Método de Pago
![Churn por Método de Pago](https://github.com/memo7499/challenge-telecom-x/blob/main/CHURN_PAGO.png)

*El método de pago electronic check está asociado a una mayor tasa de abandono frente a métodos automáticos.*


### Churn por Antigüedad del Cliente
![Churn por Antigüedad](https://github.com/memo7499/challenge-telecom-x/blob/main/CHURN_TERNURE.png)

*El abandono se concentra en los primeros meses de relación; a mayor antigüedad, menor probabilidad de churn.*

---

## 🤖 Modelo predictivo

Se entrenó un modelo de **Regresión Logística**, priorizando interpretabilidad.

- **ROC-AUC ≈ 0.83**
- Buen poder discriminatorio entre clientes que churnean y los que no

Variables con mayor impacto:
- Internet por **fibra óptica**
- **Paperless billing**
- Método de pago **electronic check**

Variables protectoras:
- Contratos de largo plazo  
- Mayor antigüedad del cliente

---

## 💡 Recomendaciones estratégicas

- Incentivar la migración de contratos mensuales a contratos de largo plazo  
- Intervenir tempranamente a clientes nuevos  
- Revisar pricing para clientes con cargos mensuales elevados  
- Promover métodos de pago automáticos  
- Fortalecer servicios de valor agregado como soporte técnico  

---

## 🔮 Próximos pasos

- Probar modelos más avanzados (Random Forest, XGBoost)  
- Construir un churn score por cliente  
- Integrar predicciones en un CRM  
- Analizar Customer Lifetime Value (CLV)  

---

## 👤 Autor

**[JUAN G SALAZAR MARTINEZ](https://www.linkedin.com/in/guillermo-sa-ma/)**

Data Analyst | Data Science Jr | Challenge Académico de Oracle ONE - Alura LATAM.
