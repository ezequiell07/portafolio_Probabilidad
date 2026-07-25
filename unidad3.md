# UNIDAD 03: Ley de los Grandes Números y Distruciones Muestrales

**Resultado de Aprendizaje (R3):** Comprende los conceptos de variable aleatoria multidimensional y distribución de probabilidad asociada, bajo los principios de solidaridad, transparencia, responsabilidad y honestidad.

---

## 1. Distribuciones Muestrales y Fundamentos Teóricos

### 1.1. Concepto de Distribución Muestral
Una **distribución muestral** es la distribución de probabilidad de un estadístico particular (como la media $\bar{X}$, la proporción $p$, o la varianza $s^2$) calculado a partir de todas las muestras posibles de un tamaño dado ($n$) extraídas de una población objetivo. 

* **Utilidad:** Permite conectar la estadística descriptiva de una muestra con la inferencia estadística sobre los parámetros de la población.
* **Comportamiento:** A medida que el tamaño de la muestra $n$ aumenta, la variabilidad de la distribución muestral disminuye.

### 1.2. Distribución de Medias Muestrales y Proporciones

#### A. Distribución de Medias Muestrales
Si se extraen muestras aleatorias de tamaño $n$ de una población con media $\mu$ y desviación estándar $\sigma$:
* **Esperanza matemática (Media):** $\mu_{\bar{X}} = \mu$
* **Error Estándar de la Media:** $\sigma_{\bar{X}} = \frac{\sigma}{\sqrt{n}}$ *(para poblaciones infinitas o muestreo con reemplazo)*
* **Factor de corrección para poblaciones finitas ($N$):** $\sigma_{\bar{X}} = \frac{\sigma}{\sqrt{n}} \sqrt{\frac{N - n}{N - 1}}$

#### B. Distribución de Proporciones Muestrales
Para variables cualitativas dicotómicas donde $p$ es la proporción poblacional de éxito y $q = 1 - p$:
* **Esperanza matemática:** $\mu_{\hat{p}} = p$
* **Error Estándar de la Proporción:** $\sigma_{\hat{p}} = \sqrt{\frac{p q}{n}}$

### 1.3. Error Estándar: Cálculo y Comportamiento
El **error estándar** mide la dispersión o variabilidad esperada de un estadístico muestral respecto al verdadero parámetro poblacional.

* **Efecto del tamaño de la muestra ($n$):** Al cuadruplicar el tamaño muestral, el error estándar se reduce a la mitad.
* **Implicación práctica:** Muestras más grandes garantizan estimaciones más precisas y menor incertidumbre en el análisis de datos.

---

## 2. Inferencia del Teorema del Límite Central (TLC) y Ley de Grandes Números

### 2.1. La Ley de los Grandes Números (LGN)
Establece que la media de los resultados obtenidos de una muestra de tamaño $n$ converge en probabilidad hacia la media poblacional $\mu$ a medida que $n \to \infty$. Garantiza la estabilidad a largo plazo de los promedios observados.

### 2.2. Deducción e Inferencia del Teorema del Límite Central (TLC)
El **Teorema del Límite Central** sostiene que si $X_1, X_2, \dots, X_n$ son variables aleatorias independientes e idénticamente distribuidas (i.i.d.) con media $\mu$ y varianza $\sigma^2 < \infty$, la suma estandarizada o la media muestral tiende a una distribución normal estándar a medida que $n \to \infty$:

$$Z = \frac{\bar{X} - \mu}{\frac{\sigma}{\sqrt{n}}} \xrightarrow{d} \mathcal{N}(0, 1)$$

> **Criterio práctico:** Por lo general, si $n \geq 30$, la aproximación normal es sumamente precisa, independientemente de la forma original de la distribución poblacional.

### 2.3. Aplicación Práctica en Entornos Reales
* **Control de Calidad Industrial:** Monitoreo del peso promedio de envases en líneas de producción.
* **Finanzas y Riesgo:** Estimación del rendimiento promedio de portafolios de inversión masivos.
* **Salud Pública:** Evaluación del impacto medio de tratamientos médicos en grandes cohortes de pacientes.

---

## 3. Análisis de Casos Estadísticos

### 3.1. Ejercicios Dirigidos y Problemas Individuales

#### Caso 1: Cálculo de Probabilidad de Medias Muestrales
Una empresa embotelladora llena refrescos con un volumen medio de $500 \text{ ml}$ y una desviación estándar de $15 \text{ ml}$. Se toma una muestra aleatoria de $n = 36$ botellas. ¿Cuál es la probabilidad de que la media de la muestra sea superior a $505 \text{ ml}$?

1. **Datos:** $\mu = 500$, $\sigma = 15$, $n = 36$, $X = 505$.
2. **Error Estándar:** $\sigma_{\bar{X}} = \frac{15}{\sqrt{36}} = 2.5$.
3. **Estandarización ($Z$):** $Z = \frac{505 - 500}{2.5} = 2.0$.
4. **Resolución:** $P(\bar{X} > 505) = P(Z > 2.0) = 1 - 0.9772 = 0.0228 \text{ (2.28\%)}$.

### 3.2. Trabajo Grupal y Análisis de Casos
* **Análisis de Votaciones y Encuestas:** Cálculo de intervalos de confianza e incertidumbre en muestras de opinión pública utilizando la distribución de proporciones.
* **Detección de Sesgos:** Identificación de errores sistemáticos vs. errores aleatorios en la recolección de datos masivos.

---

## 4. Evaluación Final y Retroalimentación de la Unidad

### 4.1. Espacio de Revisión Teórica
* Síntesis comparativa entre la **Distribución Teórica Poblacional** vs. **Distribución Muestral Empírica**.
* Discusión sobre los principios éticos aplicados: **Transparencia** en la selección muestral, **Responsabilidad** en el cálculo del margen de error y **Honestidad** en la interpretación de los resultados.

### 4.2. Guía Metodológica del Proyecto Didáctico Integrador
* **Estructura del Proyecto Final:**
  1. Definición del problema real e identificación de la variable aleatoria.
  2. Diseño del esquema de muestreo aleatorio.
  3. Aplicación empírica del TLC y prueba de la Ley de Grandes Números.
  4. Redacción del informe final con visualización de datos y conclusiones fundamentadas.
* **Criterios de Evaluación:** Precisión técnica, rigor metodológico, claridad expositiva y adhesión a los principios éticos institucionalizados.

---

# Tareas Entregadas - Portafolio Unidad 03

## ABI: Actividad Bimestral Interactiva
#### ABI 3. Distribuciones Muestrales y Ley de Grandes Números - Grupo G
- [x] 📎 [Ver Evidencia](ABI3_GrupoG.ipynb)

<hr>

## APE: Aprendizaje Práctico Experimental
#### APE 011. Distribución Muestral de Medias y Proporciones
- [x] 📎 [Ver Evidencia](APE_011_DistribucionesMuestrales.ipynb)

#### APE 012. Simulación del Teorema del Límite Central (TLC)
- [x] 📎 [Ver Evidencia](APE_012_TLC_Simulacion.ipynb)

#### APE 013. Proyecto Didáctico Integrador (Avance Final)
- [x] 📎 [Ver Evidencia](APE_013_ProyectoIntegrador.ipynb)

<hr>

## AA: Aprendizaje Autónomo
#### AA 3. Resolución de Problemas y Casos de Estudio - Grupo G
- [x] 📎 [Ver Evidencia](AA3_GrupoG.ipynb)

<hr>

## Proyecto Didáctico y Evaluación
#### Informe Final del Proyecto Didáctico
- [x] 📎 [Ver Evidencia](Proyecto_Didactico_Final_GrupoG.pdf)

## [⬅️ Regresar al menú principal](README.md)
