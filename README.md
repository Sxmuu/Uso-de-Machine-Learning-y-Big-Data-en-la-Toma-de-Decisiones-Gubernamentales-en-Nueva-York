# Uso de Machine Learning y Big Data en la Toma de Decisiones Gubernamentales en Nueva York

## Descripción

Este proyecto aplica técnicas de **Machine Learning** y **Big Data** para el análisis de indicadores territoriales en Nueva York, centrándose en la seguridad y movilidad urbana. Mediante el procesamiento y análisis de datos masivos, el objetivo es generar *insights* que apoyen la toma de decisiones gubernamentales, mejorando la gestión pública basada en evidencia.

Se emplean herramientas avanzadas como **PySpark, Pandas, Selenium, Folium**, y técnicas de **Aprendizaje Supervisado y No Supervisado**, para identificar patrones en arrestos, accidentes viales y factores socioeconómicos relevantes.

---

## 🛠 Tecnologías y Herramientas

| Tecnología               | Descripción                                    |
| ------------------------ | ---------------------------------------------- |
| **Python**               | Lenguaje principal del proyecto                |
| **PySpark**              | Procesamiento de datos a gran escala           |
| **Pandas**               | Manipulación y análisis de datos estructurados |
| **Folium**               | Visualización interactiva de mapas             |
| **Matplotlib & Seaborn** | Gráficos estadísticos y visualización de datos |
| **Selenium**             | Web scraping para extracción de datos          |
| **Scikit-Learn**         | Modelado de Machine Learning                   |

---

## 📊 Datos Utilizados

Los datos provienen de fuentes oficiales y confiables, incluyendo:

- **NYPD Arrest Data**: Registro detallado de arrestos en Nueva York.
- **NYCgov Poverty Measure Data**: Indicadores de pobreza y distribución socioeconómica.
- **Motor Vehicle Collisions – Vehicles**: Base de datos de accidentes viales en la ciudad.
- **2016 – 2017 Health Education Report**: Reporte sobre niveles de educación en Nueva York.

Estos conjuntos de datos fueron procesados y analizados para identificar correlaciones entre criminalidad, pobreza, educación y accidentes de tránsito de manera preliminar.

Finalmente, se decidió analizar principalmente el conjunto que contenía el registro detallado de arrestos en Nueva York.
---

## 📈 Metodología y Modelos Aplicados

### 1️⃣ **Análisis Exploratorio de Datos (EDA)**

- Visualización de tendencias de arrestos por mes y barrio.
- Distribución de delitos según edad, género y ubicación.
- Identificación de patrones en accidentes de tráfico.

### 2️⃣ **Preprocesamiento y Transformación**

- Limpieza de datos y manejo de valores nulos.
- Normalización y codificación de variables categóricas.
- Generación de nuevas variables relevantes.

### 3️⃣ **Modelos de Machine Learning**

#### 🔹 Modelo Supervisado: **Regresión Logística**

- Predicción del nivel de delito (*felony, misdemeanor, violation*).
- Evaluación con métricas de precisión y F1-score.

#### 🔹 Modelo No Supervisado: **K-Means Clustering**

- Segmentación geográfica de arrestos y accidentes.
- Detección de *hotspots* de criminalidad.

#### 🔹 Red Neuronal

- Se implementó una red neuronal para predicción de delitos, aunque mostró limitaciones debido a la calidad de los datos.

---

## 🌎 Visualización y Mapas Interactivos

Para facilitar la interpretación de los resultados, se generaron visualizaciones interactivas:

- **Mapa de calor de arrestos** basado en coordenadas GPS.
- **Distribución de delitos por barrio** con gráficos comparativos.
- **Análisis de correlación entre pobreza y criminalidad** mediante diagramas de dispersión.
- **Impacto de variables socioeconómicas** en la criminalidad con gráficos de tendencias.

---

## 📌 Conclusiones y Hallazgos Claves

- La criminalidad presenta una variación estacional, con picos en ciertos meses del año.
- Los **delitos menores (misdemeanors)** representan la mayor parte de los arrestos.
- Se identificaron **zonas críticas** con alta incidencia de arrestos y accidentes viales.
- Existe una relación entre **nivel socioeconómico y tasas de criminalidad**, lo que sugiere la necesidad de intervenciones en educación y empleo.
- La calidad de los datos es fundamental: modelos complejos como redes neuronales requieren datos más estructurados y completos.

---

## 🔗 Recursos y Referencias

- **NYC Open Data**
- **Scikit-Learn Documentation**
- **PySpark Guide**
- **Folium for Mapping**

---

## 👥 Contribuidores

- **Samuel Peña**
- **Tomás De Aza Márquez**
- **Juan Sebastián Córdoba Valderrama**
