# 🌍 Greenhouse Gas Emission Prediction Project

## 📌 Problem Statement

You are provided with annual supply chain emission data from 2010–2016, categorized by U.S. industries and commodities. The objective is to build a regression model that can **predict Supply Chain Emission Factors (kg CO₂e)** with margins, using various **descriptive and quality metrics** including:

- Substance type  
- Measurement unit  
- Reliability score  
- Temporal, geographical, technological, and data collection correlations

---

## 🎯 Project Goal

To analyze and predict **greenhouse gas (GHG) emissions** from U.S. supply chains by using the official dataset available on [data.gov](https://catalog.data.gov).

---

## 📁 Source

**Dataset:** [Supply Chain Greenhouse Gas Emission Factors](https://catalog.data.gov/dataset/supply-chain-greenhouse-gas-emission-factors)

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 📂 Dataset Overview

The dataset includes supply chain emission factors associated with various U.S. industries and commodities.

### Key Columns:
- `Code` – Industry classification code  
- `Industry_Name` – Name of the industry  
- `Commodity` – Item or commodity name  
- `GHG_Emissions_kgCO2e` – GHG emissions per unit (in kg CO₂ equivalent)  
- `Units` – Units of measurement (e.g., kg/2018 USD, purchaser price)

---

## 🧹 Data Preprocessing

### Steps:
- Handling missing values
- Unit conversion and consistency checks
- Encoding categorical variables
- Feature engineering based on correlation metadata
- Normalization/scaling of numeric columns

---

## 🤖 Model Building & Evaluation

### Objective:
Predict `GHG_Emissions_kgCO2e` using regression techniques.

### Models Used:
- **Linear Regression**
- **Random Forest Regressor**

### Evaluation Metrics:
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- R² Score  

---

## 🚀 Workflow

1. **Import Required Libraries**
2. **Load and Explore the Dataset**
3. **Data Preprocessing (EDA + Cleaning + Encoding)**
4. **Model Training**
5. **Prediction & Evaluation**
6. **Hyperparameter Tuning**
7. **Comparative Analysis & Best Model Selection**

---

## 📊 Expected Outcome

A reliable and interpretable regression model capable of estimating GHG emission factors for commodities across industries with high accuracy and generalizability.

---
