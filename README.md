

# 🍃 Calidad del Aire, Densidad y Arborización en Lima

**Autores:** Liz Torpoco, Rodrigo Fernandez, Tamara Bejar, André de la Fuente.
**Contexto:** Proyecto de Data Mining, Universidad del Pacífico (2026-1).

### 📌 Resumen
Análisis del impacto de la población y los árboles en la calidad del aire de Lima Metropolitana utilizando metodologías de Data Mining (CRISP-DM). 

### 🎯 Hipótesis
* **H1 (Densidad):** A mayor densidad poblacional, mayor concentración de PM2.5 (destacando los conos Norte y Este).
* **H2 (Arborización):** A mayor cantidad de árboles, menores niveles del gas contaminante NO2.

### 📊 Datos y Modelos
* **Data (577,794 registros):** SENAMHI (PM10, PM2.5, NO2), INEI (Población) y SERPAR (Árboles plantados).
* **Algoritmos propuestos:** Clustering (K-Means, DBSCAN), Reglas de Asociación (Apriori/FP-Growth) y Árboles de Decisión (CART/C4.5).

### 🚨 Insights Exploratorios
* **Villa María del Triunfo** es el distrito líder en material particulado grueso (PM10), con casi el doble del promedio de Lima.
* **San Juan de Lurigancho** encabeza las concentraciones de material fino (PM2.5) y dióxido de nitrógeno (NO2).
