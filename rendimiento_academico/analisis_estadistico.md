# Análisis de Factores en el Rendimiento Académico

Este proyecto realiza un **Análisis Estadístico Inferencial** detallado sobre los factores que influyen en el desempeño escolar de los estudiantes. Utilizando un dataset de Kaggle (*Student Performance Factors*), el estudio busca identificar variables críticas como las horas de estudio, el acceso a internet y la motivación.

**Autora:** PhD(c). Gladys Choque Ulloa  
**Especialidad:** Ciencia de Datos · Estadística · Machine Learning

## Objetivo del Proyecto
El propósito de este análisis es determinar, mediante evidencia estadística, qué factores impactan significativamente en los puntajes de los exámenes (`Exam_Score`) para fundamentar decisiones educativas basadas en datos.

## Metodología Aplicada
En este notebook (`rendimiento_academico.ipynb`), se implementaron las siguientes técnicas:

1.  **Análisis Exploratorio de Datos (EDA):** Visualización de distribuciones y estadísticas descriptivas.
2.  **Correlación de Pearson:** Para medir la relación lineal entre las horas de estudio y el puntaje obtenido.
3.  **Prueba T de Student:** Para comparar si el acceso a internet genera una diferencia significativa en el rendimiento.
4.  **ANOVA de un factor:** Para evaluar el impacto de los diferentes niveles de motivación (Baja, Media, Alta).
5.  **Prueba Chi-cuadrado de Pearson:** Para analizar la asociación entre variables cualitativas (Motivación vs. Nivel de Rendimiento).

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías principales:**
    * `Pandas` & `Numpy`: Manipulación de datos.
    * `Matplotlib` & `Seaborn`: Visualización avanzada.
    * `Scipy.stats` & `Statsmodels`: Pruebas de hipótesis estadísticas.

## Resultados Clave (Interpretación Automática)
Según las pruebas ejecutadas en el código:
* **Estudio:** Existe una correlación significativa entre las horas dedicadas y el puntaje.
* **Conectividad:** El acceso a internet es un factor determinante en la diferencia de rendimientos.
* **Psicología:** El nivel de motivación influye directamente en el éxito académico del estudiante.

## Estructura del Repositorio
* `rendimiento_academico.ipynb`: Notebook principal con todo el flujo de trabajo.
* `README.md`: Descripción del proyecto.
* *(Opcional)* `StudentPerformanceFactors.csv`: Dataset original utilizado.

---
*Este proyecto fue desarrollado con fines académicos y de investigación en ciencia de datos.*
