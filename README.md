
# 🌍 Greenhouse Gas Emission Prediction

A machine learning-powered web app built with **Streamlit** that predicts greenhouse gas (GHG) emissions based on supply chain and industry data. The goal is to support sustainability efforts by providing a quick and interactive tool for estimating emissions across various sectors.

---

## 📌 Features

- 🧠 Predict greenhouse gas emissions using ML models.
- 📈 Based on real-world industry and commodity emission data.
- 💻 Simple and intuitive Streamlit web interface.
- 🗂️ Supports input-based predictions with live results.
- 🐍 Entirely built with Python and open-source tools.

---

## 🧠 Technologies Used

| Purpose            | Tool / Library         |
|--------------------|------------------------|
| Web Interface      | [Streamlit](https://streamlit.io) |
| Data Handling      | pandas                 |
| ML Model           | scikit-learn           |
| Model Saving/Loading | joblib               |
| Deployment         | Streamlit Community Cloud |
| Dataset Format     | Excel (.xlsx)          |

---

## 🗃️ Dataset

The dataset used for training is:

```
SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx
```

It contains emission factors for U.S. industries and commodities across different years, along with various economic indicators. The model uses this historical data to learn and predict emission values for new inputs.

---

## 🤖 Machine Learning Model

- The model is trained using `scikit-learn` and saved with `joblib`.
- The script `ghg_emission_analysis.ipynb` contains data cleaning, training, and model export steps.
- The final model is loaded by the app to make predictions based on user input.

---

## ✅ To-Do / Improvements

- [ ] Add model performance metrics (MAE, R²).
- [ ] Expand dataset to include more years/regions.
- [ ] Improve UI with better charts and summaries.
- [ ] Dockerize for broader deployment options.

---

## 🙌 Acknowledgments

- Streamlit for the free deployment platform
- U.S. Environmental datasets for emission factors

---

## ⭐️ If you found this useful

Give this repo a ⭐️ and share it!
