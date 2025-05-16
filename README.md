# 🧬 Análisis de Datos – Diagnóstico Médico (Dataset Breast Cancer Wisconsin)

Notebook de limpieza, transformación y análisis exploratorio (EDA) sobre el *Breast Cancer Wisconsin (Diagnostic) Dataset*, preparando los datos para futuros modelos analíticos.

## 🎯 Objetivos

- Asegurar calidad de datos tratando valores nulos y columnas irrelevantes.
- Transformar variables para facilitar análisis.
- Explorar relaciones entre características físicas de tumores y su diagnóstico (benigno/maligno).

## 📌 Acciones Principales

- Eliminación de columnas irrelevantes (`Unnamed: 32`, `id`) y revisión de nulos (sin hallazgos).
- Transformación de `diagnosis` a binaria (`target`: 0 = benigno, 1 = maligno).
- Visualización de distribuciones y correlaciones entre variables físicas de tumores.
- Análisis dirigido para identificar diferencias entre tumores benignos y malignos.

## ✅ Conclusiones

- El 62.7% de tumores son benignos y el 37.3% malignos.
- Variables como `concave points_worst`, `perimeter_worst` y `radius_mean` son altamente predictivas.
- Tumores malignos presentan mayor tamaño, perímetro y concavidad, con distribuciones asimétricas y presencia de outliers.

## 📩 Contacto

Si tienes alguna pregunta o sugerencia, contáctame por [LinkedIn](https://linkedin.com/in/roberto-eustaquio/)
