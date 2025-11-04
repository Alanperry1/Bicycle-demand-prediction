# 🚴‍♂️ Bicycle Demand Prediction

![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Overview
This project applies **machine learning techniques** to predict **bicycle rental demand** based on environmental, weather, and temporal factors.  
Using the **Seoul Bike Sharing Dataset**, it explores how temperature, humidity, rainfall, and time of day affect usage — empowering smarter transportation and city-planning decisions.

---

## 🧠 Key Features
- ✅ Data preprocessing, cleaning, and feature engineering  
- ✅ Exploratory Data Analysis (EDA) with **Pandas**, **Seaborn**, and **Matplotlib**  
- ✅ Normalization & scaling for better model convergence  
- ✅ Implementation of multiple ML models:
  - Linear Regression  
  - Random Forest Regressor  
  - Neural Network (TensorFlow / Keras)  
  - PCA (Principal Component Analysis) for dimensionality reduction  
- ✅ Model evaluation and visualization of performance metrics  

---

## 📊 Dataset
**Source:** [Seoul Bike Sharing Demand Dataset](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand)  
**Attributes:**
- Date, Hour, Temperature, Humidity, Wind Speed, Visibility  
- Dew Point, Rainfall, Snowfall, Radiation, Functional Day Flag, and Bike Count  

> The dataset is provided by the UCI Machine Learning Repository and contains records of Seoul’s public bike usage across various weather conditions.

---

## ⚙️ Tech Stack
| Category | Technologies |
|-----------|--------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Models | Scikit-learn, TensorFlow/Keras |
| Utilities | Jupyter Notebook, Virtualenv |

---

## 🚀 Setup Instructions

```bash
# Clone repository
git clone https://github.com/<your-username>/bicycle-demand-prediction.git
cd bicycle-demand-prediction

# Create virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Bicycles.ipynb
