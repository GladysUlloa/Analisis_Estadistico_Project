# 📊 Análisis de la Matriz de Correlación — Dataset Iris

**Autora:** Gladys Choque Ulloa  
Ciencia de Datos · Estadística · Machine Learning · Investigación Cuantitativa  

---

## 📌 Descripción del Proyecto

Este proyecto presenta un análisis exploratorio profundo de la **matriz de correlación** del dataset Iris, con el objetivo de estudiar la estructura de dependencia lineal entre variables cuantitativas y sus implicaciones en modelado estadístico y aprendizaje automático.

Más allá de calcular correlaciones, este trabajo interpreta la estructura de segundo orden del sistema multivariado y evalúa posibles problemas de multicolinealidad.

---

## 📚 Contexto del Estudio

El dataset **Iris** fue introducido por el estadístico y genetista Ronald Fisher en 1936 y es uno de los conjuntos de datos más utilizados en estadística y machine learning.

Contiene 150 observaciones de flores clasificadas en tres especies:

- Setosa  
- Versicolor  
- Virginica  

Cada observación incluye cuatro variables cuantitativas:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

---

## 🎯 Objetivo

Analizar la estructura de dependencia lineal entre las variables mediante:

- Matriz de correlación de Pearson
- Visualización con heatmap
- Evaluación de multicolinealidad (VIF)
- Interpretación estadística y estructural

---

## 🧠 Preguntas de Investigación

1. ¿Existen relaciones lineales fuertes entre variables?
2. ¿Hay evidencia de redundancia informativa?
3. ¿Podría existir multicolinealidad en modelos lineales?
4. ¿Qué implicaciones tiene la estructura observada para Machine Learning?

---

## 🛠️ Metodología

El análisis se desarrolló en Python utilizando:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- statsmodels

Etapas del análisis:

1. Carga y exploración inicial del dataset
2. Estadísticos descriptivos
3. Cálculo de la matriz de correlación
4. Visualización mediante heatmap
5. Evaluación formal de multicolinealidad (VIF)
6. Interpretación estadística profunda

---

## 📊 Resultados Principales

### 🔵 Alta correlación positiva

Petal length y petal width presentan una correlación cercana a 0.96.

Esto indica:

- Fuerte relación lineal
- Posible redundancia informativa
- Riesgo de multicolinealidad en regresión

---

### 🔴 Correlaciones negativas moderadas

Sepal width muestra correlaciones negativas con variables del pétalo.

Esto sugiere una relación inversa parcial en la morfología floral.

---

### ⚪ Correlaciones débiles

Sepal length y sepal width presentan baja dependencia lineal.

---

## 📈 Evaluación de Multicolinealidad

Se calculó el Variance Inflation Factor (VIF) para cada variable.

Valores elevados confirman la presencia de redundancia estructural entre variables altamente correlacionadas.

---

## 🔬 Interpretación Estadística

La matriz de correlación estimada es una aproximación empírica de la matriz poblacional:

R = Corr(X)

Donde X es un vector aleatorio multivariado.

Propiedades relevantes:

- Matriz simétrica
- Positiva semidefinida
- Describe estructura de segundo orden

Este análisis no es meramente descriptivo, sino estructural.

---

## 🤖 Implicaciones para Machine Learning

- En regresión lineal: posible inestabilidad de coeficientes.
- En PCA: variables correlacionadas dominarán los primeros componentes.
- En clustering: posible sesgo en distancias.
- En selección de variables: necesidad de reducción dimensional.

---

## 📌 Conclusión

La matriz de correlación permite comprender la estructura interna de un sistema multivariado antes de modelar.

En el dataset Iris se observa:

- Fuerte dependencia lineal entre variables del pétalo.
- Redundancia informativa potencial.
- Implicaciones directas para estabilidad y reducción dimensional.

Este tipo de análisis es fundamental en cualquier pipeline serio de Ciencia de Datos.

---

## 📜 Licencia

Este proyecto puede utilizarse con fines educativos y académicos, citando la fuente correspondiente.

---

## 👩‍🔬 Sobre la Autora

Gladys Choque Ulloa  
PhD(c) in Computer Science 
Ciencia de Datos · Estadística · Machine Learning  
https://linktr.ee/gladyschoqueulloa


