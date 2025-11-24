# Near-Earth Object (NEO) Analysis & Hazard Prediction

This project focuses on analyzing Near-Earth Objects (NEOs) using NASA's dataset and predicting potentially hazardous objects with Machine Learning. The goal is to provide a data-driven framework for NEO risk assessment and planetary defense research.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Machine Learning Models](#machine-learning-models)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
Near-Earth Objects (NEOs) are comets and asteroids that come close to Earth's orbit. Monitoring and predicting potentially hazardous NEOs is crucial for planetary defense. This project performs:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning-based hazard prediction

---

## Dataset
The project uses **NASA's NEO dataset**, which contains detailed orbital parameters and hazard indicators of asteroids and comets.

- Source: [NASA NEO Dataset](https://ssd-api.jpl.nasa.gov/doc/cad.html)
- Features include:
  - `orbital_parameters` (e.g., semi-major axis, eccentricity)
  - `physical_characteristics` (e.g., diameter, velocity)
  - `hazard_indicator` (boolean)

---

## Technologies Used
- **Programming Language:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn, Plotly  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Evaluation:** ROC-AUC, Cross-Validation  

---

## Features
- Cleaned and preprocessed raw NASA NEO data  
- Engineered meaningful features for hazard prediction  
- Visualized orbital parameters and potential hazards  
- Built ML models to classify hazardous objects  
- Tuned hyperparameters and evaluated models for optimal performance  

---

## Machine Learning Models
- **Random Forest Classifier** – ensemble-based model for classification  
- **Logistic Regression** – baseline model for binary classification  
- **XGBoost Classifier** – gradient boosting for improved accuracy  

**Evaluation Metrics:**
- ROC-AUC Score  
- Accuracy  
- Cross-Validation for model robustness  

---

## Installation
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/NEO-Hazard-Prediction.git
