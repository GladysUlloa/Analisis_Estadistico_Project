# Pruebas de Normalidad en Ciencia de Datos

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-green?logo=scikitlearn) ![Estado](https://img.shields.io/badge/Estado-En%20progreso-orange)

**Autora:** PhD(c). Gladys Choque Ulloa in Computer Science

**Tema:** Estadística aplicada · Ciencia de Datos · Machine Learning · Inferencia estadística

---

## Descripción

Este repositorio presenta un análisis completo sobre **pruebas de normalidad**, combinando fundamentos teóricos, pruebas formales y aplicaciones prácticas en un **dataset clínico real**.  
El objetivo es demostrar cómo evaluar la normalidad de variables y residuos de modelos lineales, y cómo esta evaluación impacta la inferencia estadística.

El proyecto incluye:

- Explicación teórica de la normalidad y su importancia en estadística e inferencia.
- Pruebas estadísticas formales: Shapiro-Wilk, Anderson-Darling, Kolmogorov-Smirnov.
- Visualizaciones gráficas para diagnóstico de normalidad (histogramas, KDE, QQ-plots).
- Aplicación a un **dataset clínico real** sobre telemonitoreo de Parkinson.
- Evaluación de normalidad de residuos de un modelo lineal.
- Visualizaciones animadas y exportación de GIFs.

---

## Contexto de estudio 
**Dataset:** [University of California Irvine Parkinson's Telemonitoring Dataset](https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring)  

### Contexto clínico

El dataset contiene **5,875 grabaciones de voz de 42 pacientes con Parkinson en etapa temprana**.  
Se recopilaron medidas acústicas de la voz para evaluar remotamente la progresión clínica de la enfermedad (UPDRS).

- Telemonitoreo de la progresión del Parkinson.
- Creado por investigadores de la Universidad de Oxford.
- Referencia: A. Tsanas et al. (2009) – *IEEE Transactions on Biomedical Engineering*.

### Pregunta de investigación

1. ¿Las variables acústicas cumplen el supuesto de normalidad? 
2. ¿Los residuos de un modelo lineal cumplen el supuesto de normalidad?  
3. ¿Qué implicaciones tiene esto para la inferencia estadística y la validez del modelo?

---

## Estructura del análisis

El análisis se realizó en seis etapas principales:

1. **Carga y contexto:**  
   - Exploración inicial del dataset.  
   - Selección de variables relevantes: `motor_updrs`, `jitter`, `shimmer`, `ppe`.  

2. **Normalidad en variables clave:**  
   - Exploración visual: histogramas y KDE.  
   - Diagnóstico gráfico con QQ-plots.  

3. **Pruebas formales de normalidad:**  
   - Shapiro-Wilk para muestras pequeñas.  
   - Anderson-Darling para la distribución completa.  
   - Evaluación de la adecuación de las pruebas según tamaño de muestra.  

4. **Modelo lineal:**  
   - Predicción de `motor_updrs` usando biomarcadores vocales.  
   - Extracción de residuos para evaluación de supuestos.  

5. **Normalidad de residuos:**  
   - Shapiro-Wilk y QQ-plots para diagnosticar residuos del modelo.  
   - Interpretación de resultados y su implicancia en inferencia.  

6. **Visualizaciones animadas y exportación GIF:**  
   - Evolución de histograma hacia QQ-plot.  
   - Generación de GIFs para mostrar visualmente la normalidad de los residuos.

---

## Contenido del repositorio

- `notebooks/`: Notebook con análisis paso a paso, visualizaciones y pruebas de normalidad.  
- `scripts/`: Scripts Python listos para ejecutar los análisis.  
- `data/`: Dataset de ejemplo (Parkinson’s Telemonitoring Dataset).  
- `images/`: Gráficos y visualizaciones generadas durante el análisis.  
- `README.md`: Este documento con la explicación del proyecto.

---

## Objetivo profesional

Este repositorio busca demostrar:

- Aplicación práctica de pruebas de normalidad a datos clínicos reales.  
- Evaluación rigurosa de supuestos estadísticos para modelos lineales.  
- Integración de teoría, visualización y código reproducible.  

Es ideal como ejemplo avanzado para estudiantes de **Ciencia de Datos, Estadística Aplicada y Machine Learning**.

---

## Licencia

Este proyecto se distribuye bajo **MIT License**.

---
