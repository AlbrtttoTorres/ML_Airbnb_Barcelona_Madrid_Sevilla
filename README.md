# ML_Airbnb_Barcelona_Madrid_Sevilla
# 📌 Proyecto: Análisis y Predicción de Alojamientos en Barcelona, Madrid y Sevilla

## 📖 Descripción
Este proyecto tiene como objetivo analizar un conjunto de datos de alojamientos en Airbnb en las ciudades de **Barcelona, Madrid y Sevilla**. A través de un proceso de **Exploración de Datos (EDA)** y la aplicación de modelos de **Machine Learning (ML) y Deep Learning (DL)**, buscamos identificar patrones y predecir variables clave como **el precio de los alojamientos**.

---
## 📂 Estructura del Proyecto

```
/
|-- data/                    # Datos crudos y preprocesados
|   |-- dataset_original.csv  # Dataset inicial sin modificaciones
|   |-- dataset_limpio.csv    # Dataset preprocesado y limpio
|
|-- notebooks/               # Notebooks de análisis y modelado
|   |-- 01_EDA.ipynb         # Exploración y visualización de datos
|   |-- 02_Feature_Engineering.ipynb # Creación y selección de características
|   |-- 03_Machine_Learning.ipynb   # Modelos de ML para predicción
|   |-- 04_Deep_Learning.ipynb      # Modelos de DL con redes neuronales
|
|-- models/                  # Modelos entrenados
|   |-- ml_model.pkl         # Modelo de ML guardado
|   |-- dl_model.h5          # Modelo de DL guardado
|
|-- src/                     # Código fuente
|   |-- preprocessing.py     # Funciones de limpieza y transformación de datos
|   |-- train_ml.py          # Entrenamiento de modelos de ML
|   |-- train_dl.py          # Entrenamiento de redes neuronales
|
|-- README.md                # Este archivo con la descripción del proyecto
|-- requirements.txt         # Librerías necesarias para ejecutar el código
```

---
## 🚀 Tecnologías Utilizadas
- **Python 3.x**
- **Pandas, NumPy** (Manipulación de datos)
- **Matplotlib, Seaborn, Plotly** (Visualización de datos)
- **Scikit-learn** (Modelos de Machine Learning)
- **TensorFlow, Keras** (Redes neuronales y Deep Learning)

---
## 🔍 Análisis Exploratorio de Datos (EDA)
Durante esta etapa, se realizaron las siguientes tareas:
- Limpieza y tratamiento de valores nulos
- Distribución de precios y otros atributos clave
- Análisis de correlación entre variables
- Identificación de outliers y anomalías

---
## 🤖 Modelado con ML y DL

### **1️⃣ Modelos de Machine Learning (ML)**
Se probaron distintos modelos para predecir los precios de los alojamientos:
- **Regresión Lineal**
- **Árboles de Decisión**
- **Random Forest**
- **Gradient Boosting (XGBoost, LightGBM)**

📌 *Mejor modelo obtenido: Random Forest Classifier

### **2️⃣ Modelos de Deep Learning (DL)**
Se implementó una Red Neuronal con la siguiente arquitectura:
- Capa de entrada con **variables normalizadas**
- 2 capas ocultas con **activación ReLU**
- Capa de salida con una neurona para **predicción del precio**

📌 *Resultados: la red neuronal superó a los modelos tradicionales con un error menor en el conjunto de prueba.*

---
## 📊 Visualizaciones
Algunas gráficas generadas incluyen:
- Mapa de calor de correlaciones
- Histogramas de distribución de precios
- Gráficos de dispersión entre precio y otras variables
- Mapas de densidad de alojamientos por ciudad

---
## 🛠 Instalación y Uso
### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/usuario/proyecto-airbnb.git
cd proyecto-airbnb
```

### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3️⃣ Ejecutar los notebooks
Abre Jupyter Notebook y ejecuta los archivos dentro de `notebooks/`.

```bash
jupyter notebook
```

### 4️⃣ Entrenar modelos
Para entrenar los modelos de ML y DL, ejecuta:
```bash
python src/train_ml.py
python src/train_dl.py
```

---
## 📌 Conclusiones
- Existen diferencias de precios significativas entre las ciudades.
- La disponibilidad y número de reseñas influyen en el precio.
- Modelos de ML y DL pueden predecir el precio con buena precisión.
- Modelos de ML y DL pueden predecir epocas de alta y baja demanda con buena precisión.


¡Esperamos que este proyecto sea útil y sirva como referencia para futuros análisis! 🚀

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

ML_Airbnb_Barcelona_Madrid_Seville
📌 Project: Analysis and Prediction of Listings in Barcelona, Madrid, and Seville
📖 Description
This project aims to analyze a dataset of Airbnb listings in the cities of Barcelona, Madrid, and Seville. Through a process of Exploratory Data Analysis (EDA) and the application of Machine Learning (ML) and Deep Learning (DL) models, we seek to identify patterns and predict key variables such as listing prices.

📂 Project Structure
bash
Copiar
Editar
/
|-- data/                    # Raw and preprocessed data
|   |-- dataset_original.csv  # Initial unmodified dataset
|   |-- dataset_limpio.csv    # Preprocessed and clean dataset
|
|-- notebooks/               # Analysis and modeling notebooks
|   |-- 01_EDA.ipynb         # Data exploration and visualization
|   |-- 02_Feature_Engineering.ipynb # Feature creation and selection
|   |-- 03_Machine_Learning.ipynb   # ML models for prediction
|   |-- 04_Deep_Learning.ipynb      # DL models using neural networks
|
|-- models/                  # Trained models
|   |-- ml_model.pkl         # Saved ML model
|   |-- dl_model.h5          # Saved DL model
|
|-- src/                     # Source code
|   |-- preprocessing.py     # Data cleaning and transformation functions
|   |-- train_ml.py          # ML model training
|   |-- train_dl.py          # Neural network training
|
|-- README.md                # This file with the project description
|-- requirements.txt         # Required libraries to run the code
🚀 Technologies Used
Python 3.x

Pandas, NumPy (Data manipulation)

Matplotlib, Seaborn, Plotly (Data visualization)

Scikit-learn (Machine Learning models)

TensorFlow, Keras (Neural networks and Deep Learning)

🔍 Exploratory Data Analysis (EDA)
During this stage, the following tasks were carried out:

Cleaning and handling of missing values

Distribution of prices and other key attributes

Correlation analysis between variables

Identification of outliers and anomalies

🤖 ML and DL Modeling
1️⃣ Machine Learning (ML) Models
Different models were tested to predict listing prices:

Linear Regression

Decision Trees

Random Forest

Gradient Boosting (XGBoost, LightGBM)

📌 Best performing model: Random Forest Classifier

2️⃣ Deep Learning (DL) Models
A Neural Network was implemented with the following architecture:

Input layer with normalized variables

2 hidden layers with ReLU activation

Output layer with a single neuron for price prediction

📌 Results: the neural network outperformed traditional models with lower error on the test set.

📊 Visualizations
Some generated plots include:

Correlation heatmap

Price distribution histograms

Scatter plots between price and other variables

Density maps of listings by city

🛠 Installation and Usage
1️⃣ Clone the repository
bash
Copiar
Editar
git clone https://github.com/usuario/proyecto-airbnb.git
cd proyecto-airbnb
2️⃣ Install dependencies
bash
Copiar
Editar
pip install -r requirements.txt
3️⃣ Run the notebooks
Open Jupyter Notebook and run the files inside the notebooks/ folder.

bash
Copiar
Editar
jupyter notebook
4️⃣ Train models
To train the ML and DL models, run:

bash
Copiar
Editar
python src/train_ml.py
python src/train_dl.py
📌 Conclusions
There are significant price differences between the cities.

Availability and number of reviews influence the price.

ML and DL models can predict price with good accuracy.

ML and DL models can also predict high and low demand periods with good accuracy.

We hope this project is useful and serves as a reference for future analyses! 🚀

