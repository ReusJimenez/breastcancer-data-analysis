# 🧬 **BreastCancer – Data Wrangling & EDA**  

Este repositorio contiene un notebook enfocado en la **limpieza**, **transformación** y **análisis exploratorio de datos (EDA)** del dataset *Breast Cancer*. El objetivo principal es preparar los datos para futuras aplicaciones analíticas o predictivas, mediante un proceso estructurado y reproducible.

## 📁 **Contenido del Notebook**  

- Exploración inicial del dataset
- Tratamiento de valores faltantes
- Eliminación de columnas irrelevantes
- Transformación de variables para facilitar el análisis
- Análisis exploratorio (EDA) visual y estadístico
- Respuestas a preguntas clave para identificar patrones entre tumores benignos y malignos

## 🎯 **Objetivo del Análisis**  

El propósito es dejar el dataset en condiciones óptimas para futuros modelos de machine learning o análisis más avanzados, abordando tareas como:

- Identificar y eliminar datos innecesarios o nulos
- Transformar variables categóricas a numéricas
- Comprender la distribución y relación de las variables
- Detectar patrones relevantes para el diagnóstico de cáncer de mama

## 🧰 **Tecnologías Utilizadas**  

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## 📁 **Dataset Utilizado**  

- Fuente: Breast Cancer Wisconsin (Diagnostic) Dataset
- Formato: CSV
- Columnas originales: 33 (tras limpieza: 31)
- Variable objetivo: `diagnosis`, transformada a `target` (0 = Benigno, 1 = Maligno)

## 📌 **Principales acciones realizadas**  

### 🧹 Limpieza y preparación de datos
- Eliminación de columnas irrelevantes (`Unnamed: 32`, `id`)
- Conversión de la variable `diagnosis` a formato binario (`target`)
- Revisión de valores nulos (no se detectaron tras limpieza)

### 📊 Análisis Exploratorio (EDA)
- Visualización de la distribución de clases (desbalance leve)
- Análisis de variables como `radius_mean` y `texture_mean`
- Matriz de correlación para identificar las variables más relevantes
- Uso de boxplots y countplots para comparar distribuciones

### ✅ Conclusiones Clave
- El 62.7% de los tumores son benignos y el 37.3% malignos.
- Variables como `concave points_worst`, `perimeter_worst` y `radius_mean` tienen alta correlación con el diagnóstico.
- Los tumores malignos tienden a tener valores más altos en tamaño, perímetro y concavidad.
- Las distribuciones presentan asimetría y valores extremos, especialmente en tumores malignos.

## 🔜 **Próximos Pasos**  

- Aplicar técnicas de escalado y normalización
- Entrenar modelos de clasificación supervisada
- Validar métricas de desempeño y evaluar interpretabilidad del modelo

## 📩 **Contacto**  

Si tienes alguna pregunta o sugerencia, no dudes en contactar a:

- **Nombre:** Roberto Edmundo Eustaquio Jiménez  
- **Email:** [reusjimenez2002@gmail.com](mailto:reusjimenez2002@gmail.com)  
- **GitHub:** [https://github.com/ReusJimenez](https://github.com/ReusJimenez)  
- **LinkedIn:** [https://linkedin.com/in/roberto-eustaquio/](https://linkedin.com/in/roberto-eustaquio/)  

## 📜 **Licencia**  

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más información.  
