# bda-modulo-3-evaluacion-final-PatriciaAnaya

# Análisis de Actividad y Lealtad de Clientes de Aerolínea ✈️

**Análisis de Comportamiento de Clientes** es un proyecto de análisis de datos enfocado en el **estudio del comportamiento, lealtad y duración de relación de clientes de una aerolínea**. Utilizando dos datasets complementarios: **Customer_Flight_Activity.csv** y **Customer_Loyalty_History.csv**, se ha realizado un análisis profundo del comportamiento de compra, acumulación de puntos y patrones de retención.

El objetivo principal es identificar patrones clave en la actividad de vuelos, analizar variables socioeconómicas (salario, educación, estado civil), evaluar la efectividad de los programas de lealtad y determinar los factores que influyen en la retención de clientes mediante análisis de supervivencia.

---

## 👥 Equipo y Metodología

Este proyecto se ha desarrollado como **evaluación final del Módulo 3** del programa de Data Analytics de Adalab. Se ha seguido un enfoque riguroso basado en **análisis exploratorio de datos (EDA)** y **métodos estadísticos avanzados** para garantizar conclusiones sólidas y reproducibles.

* **Autora:** Patricia Anaya.
* **Análisis incluidos:**
    * Exploración y limpieza de datos.
    * Estadísticas descriptivas detalladas.
    * Análisis de correlaciones.
    * Visualizaciones multidimensionales.
    * Evaluación de diferencias por niveles educativos.
    * Análisis de supervivencia con Kaplan-Meier.

---

## 🛠️ Tecnologías Utilizadas

Para el desarrollo del análisis exploratorio y estadístico, se han empleado las siguientes herramientas:

* **Lenguaje:** Python 3.x.
* **Librerías principales:**
    * `Pandas` y `NumPy`: Para la manipulación, limpieza y transformación de datos.
    * `Matplotlib` y `Seaborn`: Para la generación de visualizaciones de calidad profesional.
    * `SciPy`: Para análisis estadísticos y cálculos de correlación.
    * `Lifelines`: Para análisis de supervivencia mediante el método Kaplan-Meier.
    * `Jupyter Notebook`: Para la documentación interactiva del análisis.

---

## 🚀 Estructura del Proyecto

El análisis se estructura en los siguientes componentes principales documentados en el notebook:

1. **Conexiones e Importaciones:**
    * Carga de bibliotecas necesarias (pandas, numpy, matplotlib, seaborn, lifelines).
    * Lectura de datasets CSV: `Customer_Flight_Activity.csv` y `Customer_Loyalty_History.csv`.
    * Función de homogeneización de nombres de columnas.

2. **Exploración de Datos:**
    * Información general de cada dataset (dimensiones, tipos de datos).
    * Análisis de valores nulos y duplicados.
    * Estadísticas descriptivas básicas.
    * Identificación y tratamiento de valores negativos.

3. **Limpieza y Transformación:**
    * Conversión de fechas a formato datetime.
    * Creación de columna de estado (Activo/Cancelado).
    * Merge de ambos datasets por Loyalty Number.

4. **Análisis Estadístico:**
    * Estadísticas descriptivas por variable numérica (salario, CLV, vuelos, distancia, puntos).
    * Cálculo de correlaciones entre variables.
    * Análisis de variables categóricas (tarjeta de fidelidad, educación, género, provincia, estado civil).

5. **Visualización y Insights:**
    * Distribución temporal de vuelos (patrones por mes).
    * Relación distancia-puntos segmentada por tipo de tarjeta.
    * Distribución geográfica de clientes.
    * Análisis de salarios por nivel educativo.
    * Composición de tipos de tarjetas de fidelidad.
    * Análisis demográfico (género, estado civil).

6. **Evaluación Avanzada:**
    * Análisis de diferencias en reservas de vuelos por nivel educativo.
    * Densidades y distribuciones por education level.

7. **Bonus - Análisis de Supervivencia:**
    * Cálculo de tenure (meses de permanencia).
    * Curva de Kaplan-Meier general.
    * Curvas de supervivencia segmentadas por tipo de tarjeta de fidelidad.

---

## 📊 Insights Clave

A través del análisis realizado, el proyecto responde a preguntas estratégicas como:

* **Patrones de Vuelos:** Los meses de verano (julio, agosto) y diciembre registran picos claros de reservas, coincidiendo con periodos vacacionales.

* **Programa de Puntos:** Existe una correlación positiva fuerte entre vuelos y distancia (r ≈ 1), así como entre vuelos y puntos acumulados. Sin embargo, la correlación entre puntos acumulados y canjeados es baja, indicando que más de la mitad de clientes no canjean puntos.

* **Impacto de Tarjetas de Fidelidad:** El tipo de tarjeta (Star, Nova, Aurora) determina el ratio de puntos por distancia, generando cuatro tendencias distintas.

* **Variables Socioeconómicas:** El nivel educativo predice moderadamente el salario. Doctorados presentan mayor dispersión y outliers. Paradójicamente, salario y CLV muestran correlación negativa.

* **Distribución Geográfica:** Mayor concentración de clientes en áreas urbanas grandes (Ontario, Quebec, British Columbia).

* **Composición Demográfica:** El 58% de clientes son casados. Género no es un diferenciador significativo. La educación universitaria es dominante (duplica otros niveles).

* **Reservas por Educación:** No existe relación significativa entre nivel educativo y número de vuelos reservados (tendencia prácticamente lineal).

* **Retención de Clientes:** Los primeros 15-20 meses son críticos para el churn. Después de este periodo, los clientes presentan alta lealtad. El tipo de tarjeta no muestra diferencias significativas en supervivencia.

---

## ⚙️ Datos y Archivos

* **Customer_Flight_Activity.csv:** 405,624 registros de actividad mensual de clientes (9 variables: Loyalty Number, Month, Flights Booked, Total Flights, Distance, Points Accumulated, Points Redeemed, Flights with Companions).

* **Customer_Loyalty_History.csv:** 16,737 registros únicos de clientes (15 variables: datos demográficos, tipo de tarjeta, fechas de inscripción/cancelación, salario, CLV).

* **bda-modulo-3-evaluacion-final-PatriciaAnaya.ipynb:** Notebook completo con todo el análisis, visualizaciones y conclusiones.
