# Agrupamiento No Supervisado con K-Means sobre el Dataset `inf_01.csv`

Este proyecto tiene como objetivo entrenar un modelo de *Machine Learning* no supervisado para agrupar los datos contenidos en el dataset `inf_01.csv`, utilizando la técnica de clustering **K-Means**. Se realiza un análisis exploratorio completo y se aplican métricas de evaluación para validar la calidad del agrupamiento.

## 🧠 Enfoque del Proyecto

El modelo utiliza técnicas no supervisadas para identificar patrones y segmentar los datos sin etiquetas previas. Esto permite descubrir grupos naturales dentro del dataset mediante el uso del algoritmo **K-Means**.

## 🛠️ Tecnologías y Herramientas

- **Entorno**: Anaconda - Jupyter Notebook (Windows)
- **Lenguaje**: Python 3.12.7
- **Librerías utilizadas**:
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## 📊 Metodología

1. **Análisis Exploratorio de Datos (EDA)**
   - Detección y eliminación de **valores duplicados**
   - Identificación de **valores nulos**
   - Exploración de **patrones y relaciones entre variables**
   - Generación de una **matriz de correlación de Pearson**
   - Identificación y tratamiento de **outliers**

2. **Determinación del número óptimo de clusters**
   - Uso del método **Elbow (Codo)** para definir el valor de `k`

3. **Entrenamiento del modelo**
   - Aplicación del algoritmo **K-Means** para el agrupamiento

4. **Evaluación del modelo**
   - Cálculo del **Silhouette Score** para evaluar la cohesión y separación entre clusters

## 📁 Estructura del Repositorio

├── data/ │ └── inf_01.csv # Dataset original ├── notebooks/ │ └── clustering_kmeans.ipynb # Notebook con el análisis y entrenamiento del modelo ├── README.md 

# Documentación del proyecto


## 📌 Notas

- El dataset debe colocarse en la carpeta `data/` con el nombre exacto `inf_01.csv`.
- Asegúrate de tener instaladas todas las dependencias listadas para ejecutar correctamente el notebook.

## 🚀 Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```
2. Abre el entorno Jupyter Notebook:

  ```bash
  jupyter notebook
  ```
  
