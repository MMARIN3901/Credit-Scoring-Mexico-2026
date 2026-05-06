# Credit Scoring & Stress Testing: Escenario México 2026 🇲🇽

## Visión del Proyecto
Este proyecto no es solo un modelo predictivo; es una herramienta de **estabilidad financiera** diseñada para la banca comercial en México. El objetivo es anticipar el deterioro de la cartera de crédito ante el entorno macroeconómico proyectado para 2026, integrando variables de riesgo tradicional con choques de inflación y tasas de interés.

## Arquitectura del Pipeline
El flujo de trabajo sigue el ciclo de vida real de un proyecto de Analytics en una institución financiera:

1. **Ingesta de Datos (SQL)**: Extracción de variables de originación y comportamiento mediante consultas robustas diseñadas para entornos de Big Data.
2. **Análisis de Cosechas (Vintage Analysis)**: Monitoreo del comportamiento histórico por mes de apertura para identificar tendencias de impago temprano.
3. **Simulación de Stress Test**: Ajuste de la capacidad de pago real de los clientes basándose en proyecciones del **INPC** (Inflación) y la tasa de referencia de **Banxico**.
4. **Modelado Predictivo (Machine Learning)**: Implementación de un algoritmo de **Random Forest** para clasificar el riesgo en un entorno de alta incertidumbre.
5. **Explicabilidad (XAI)**: Análisis de la importancia de variables para asegurar que las decisiones del modelo sean transparentes y auditables ante la **CNBV**.

## 📊 Resultados de Negocio
* **Optimización de Recuperación**: El modelo identifica clientes en riesgo con una precisión superior a las reglas de negocio fijas tradicionales.
* **Reducción del IMOR**: Permite una gestión preventiva del Índice de Morosidad al detectar patrones de estrés financiero antes de que ocurra el incumplimiento.
* **Resiliencia Macroeconómica**: Validación del impacto directo del incremento en el costo del dinero sobre el **DTI (Debt-to-Income)** de los acreditados.

## 🛠️ Tecnologías Utilizadas
* **Lenguajes**: SQL, Python.
* **Librerías**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib.
* **Enfoque**: Riesgo de Crédito, Analytics Translator, Business Intelligence.

---
**Desarrollado por:** Moisés Antonio Marín Bernal  
*Líder Senior en Strategic Procurement & Supply Chain | Aspirante a Analytics Translator & Risk Analyst*
