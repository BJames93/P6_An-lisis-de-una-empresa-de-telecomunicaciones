# P6_An-lisis-de-una-empresa-de-telecomunicaciones
Proyecto Tripleten proyecto 6

**Sprint 7**
Este repositorio contiene el análisis realizado de una empresa de telecomunicaciones "Connecta Tel" con operaciones en Mexico y Colombia. 

# Proyecto de Análisis de Datos: ConnectaTel

## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es realizar un análisis exploratorio de datos (EDA) y una segmentación de clientes para la empresa ConnectaTel. A través de este análisis, buscamos identificar patrones de consumo en servicios de voz y mensajería, detectar comportamientos atípicos (outliers) y categorizar a los usuarios en segmentos clave para proponer estrategias comerciales informadas.

## 📊 Datasets Utilizados
El análisis se basa en el dataset de perfiles de usuario (user_profile), el cual contiene información clave como:

- Datos demográficos: age (edad) del usuario.
- Patrones de uso: cant_mensajes, cant_llamadas y cant_minutos_llamada.
- Información de servicio: plan (tipo de suscripción: Básico/Premium) y segmentaciones calculadas (grupo_uso, grupo_edad).

## 🔍 Etapas del Análisis
El flujo de trabajo se divide en las siguientes etapas técnicas:

1. Limpieza y Preparación: Manejo de valores nulos, especialmente en la columna de minutos de llamadas, asegurando la integridad del dataset.

2. Análisis Exploratorio (EDA): Visualización de las distribuciones de uso mediante histogramas y análisis de densidad para entender el comportamiento general.

3. Detección de Outliers: Identificación de casos extremos mediante diagramas de caja (boxplots) y validación estadística utilizando el método del Rango Intercuartílico (IQR).

4. Segmentación de Clientes: Creación de nuevas variables categóricas para clasificar a los usuarios según su nivel de uso y grupo de edad.

5. Análisis Ejecutivo: Síntesis de hallazgos para la toma de decisiones, proponiendo recomendaciones estratégicas para el negocio.

## 🚀 Cómo ejecutar el Notebook
Este proyecto está diseñado para ejecutarse de forma sencilla en entornos de notebook:

Google Colab (Recomendado):

Haz clic en el botón "Open in Colab" si está disponible, o sube el archivo .ipynb directamente a Google Colab.

Asegúrate de cargar el archivo de datos necesario en el entorno de archivos de Colab.

Entorno Local:

Asegúrate de tener instalada una distribución de Python (como Anaconda) o un entorno virtual.

Instala las dependencias necesarias: pip install pandas seaborn matplotlib.

Abre el archivo con Jupyter Notebook o VS Code.

## 🛠️ Guía de Reproducción
Para reproducir los resultados obtenidos:

Clona este repositorio o descarga el archivo S7 Version-Estudiante-Project-ConnectaTel.ipynb.

Ejecuta las celdas de importación de librerías primero.

Asegúrate de ejecutar las celdas de limpieza de datos antes de intentar generar las visualizaciones o los cálculos de límites IQR, ya que el orden de ejecución es fundamental para evitar errores de tipo KeyError.

Sigue la estructura de bloques numerados del notebook para replicar cada uno de los gráficos presentados.
