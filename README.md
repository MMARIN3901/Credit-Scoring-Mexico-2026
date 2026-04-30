# AI Credit Scoring Model - Estrategia México 2026

## 📌 Visión del Proyecto
Este repositorio contiene un modelo de **Machine Learning** diseñado para la evaluación de riesgo crediticio en un entorno macroeconómico volátil. A diferencia de los modelos estáticos tradicionales, esta arquitectura integra variables de sensibilidad financiera para el contexto mexicano de 2026.

## 🛠️ Innovación Técnica
El modelo utiliza un enfoque de **Feature Engineering** avanzado para inyectar realismo económico:
*   **Ajuste por Inflación (INPC):** Deflactación del ingreso nominal para calcular la capacidad de pago real.
*   **Estrés de Tasas (Banxico):** Simulación de capacidad de pago ante un incremento de +200 puntos base en la tasa de referencia.
*   **Algoritmo:** Implementación de **Random Forest** para clasificación de riesgo (Bajo, Medio, Alto).

## 📂 Estructura del Repositorio
*   `notebooks/`: Contiene el análisis completo, desde la ingesta de datos hasta el entrenamiento del modelo y visualización de resultados.
*   `data/`: Dataset generado con variables sintéticas estresadas bajo criterios de riesgo bancario.

## 📈 Resultados
El modelo permite una segmentación precisa de clientes, cumpliendo con criterios de explicabilidad necesarios para la normativa de la **CNBV**, identificando el **DTI Estresado** como la variable con mayor peso predictivo.

---
**Desarrollado por:** Moisés Antonio Marín Bernal  
*Experto en Sourcing Estratégico & Analista de Datos en Proceso*
