# **README: Análisis y Visualización de Parámetros Críticos en Agua Subterránea**

## 📌 Índice
- [📝 Sobre el Proyecto](#-sobre-el-proyecto)
- [⚡ Características principales](#-características-principales)
- [🔧 Posibles mejoras](#-posibles-mejoras)
- [👨‍💻 Tecnologías utilizadas](#-tecnologías-utilizadas)
- [⚙ Instalación y uso en Google Colab](#-instalación-y-uso-en-google-colab)
- [📂 Estructura del proyecto](#-estructura-del-proyecto)
- [🌟 Estado del proyecto](#-estado-del-proyecto)

---

## 📝 **Sobre el Proyecto**
**PROYECTO_4-_REDES** es un sistema desarrollado en Python que permite analizar y visualizar parámetros críticos en agua subterránea, como **nitratos**, **arsénico**, **tricloroetileno** y **tetracloruro de carbono**. El objetivo principal es facilitar la toma de decisiones mediante la limpieza, análisis y visualización de datos provenientes de muestreos de agua.

El sistema incluye las siguientes funcionalidades:
- **Carga y limpieza de datos:** Procesa archivos Excel eliminando filas/columnas vacías, normalizando nombres de columnas y manejando valores faltantes.
- **Análisis Exploratorio de Datos (EDA):** Genera estadísticas descriptivas y detecta valores faltantes.
- **Visualización de datos:** Crea gráficos de barras apiladas para analizar la distribución de parámetros por región y rango, así como histogramas de cantidad de muestras por región.
- **Identificación de valores fuera de norma:** Detecta y visualiza pozos con concentraciones superiores a los límites regulatorios.

---

## ⚡ **Características principales**
✅ Limpieza y normalización de datos provenientes de archivos Excel.  
✅ Análisis de parámetros críticos: nitratos, arsénico, tricloroetileno y tetracloruro de carbono.  
✅ Gráficos de barras apiladas con porcentajes dentro de las barras para cada parámetro.  
✅ Eliminación de datos no relevantes, como regiones o distritos "NO DETERMINADA".  
✅ Identificación de pozos con valores fuera de norma según los límites regulatorios.  
✅ Exportación de datos limpios a formatos Excel y CSV.  

---

## 🔧 **Posibles mejoras**
❌ Implementar un sistema de predicción para la evolución de parámetros críticos.  
❌ Agregar más opciones de visualización, como gráficos de líneas para tendencias temporales.  
❌ Optimizar el manejo de grandes volúmenes de datos para mejorar el rendimiento.  
❌ Automatizar la generación de informes ejecutivos en formato PDF.  

---

## 👨‍💻 **Tecnologías utilizadas**
- **Lenguaje de programación:** Python  
- **Librerías principales:**  
  - `pandas`: Para la manipulación y análisis de datos.  
  - `numpy`: Para cálculos numéricos.  
  - `matplotlib` y `seaborn`: Para la creación de gráficos.  
- **Entorno de trabajo:** Google Colab  

---

## ⚙ **Instalación y uso en Google Colab**

### **1. Abrir el proyecto en Google Colab**
1. Accede al archivo del proyecto en el repositorio de GitHub:  
   [PROYECTO_4-_REDES](https://github.com/MaximilianoScarlato/PROYECTO_4-_REDES.git)  
2. Descarga el archivo `proyecto_4_Redes.ipynb` o ábrelo directamente en Google Colab.

### **2. Subir el archivo de datos**
1. Ejecuta la celda correspondiente para cargar el archivo Excel con los datos de muestreo.  
2. Sube el archivo desde tu computadora cuando se solicite.

### **3. Ejecutar el análisis**
1. Ejecuta las celdas del notebook en orden para realizar las siguientes tareas:  
   - Cargar y limpiar los datos.  
   - Realizar el análisis exploratorio (EDA).  
   - Visualizar los datos mediante gráficos.  
   - Identificar valores fuera de norma.  
2. Los resultados se mostrarán directamente en el notebook.

---

## 📂 **Estructura del proyecto**

PROYECTO_4-_REDES
├── proyecto_4_Redes.ipynb       # Notebook principal del proyecto
├── datos_muestra.xlsx           # Archivo de datos de entrada (ejemplo)
├── datos_limpios_preview.csv    # Archivo de datos limpios (salida)
├── README.md                    # Documentación del proyecto

## 🌟 **Estado del proyecto**
El proyecto está en desarrollo. Se han implementado las funcionalidades principales, pero aún hay áreas que requieren mejoras y optimización.  

Si este proyecto te resulta útil, ¡marca el repositorio con una estrella en GitHub! ⭐
