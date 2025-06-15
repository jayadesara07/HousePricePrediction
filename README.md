# 🏠 Housing Price Prediction Model

This project presents a regression-based machine learning model for predicting housing prices using a dataset of housing features. The work includes data preprocessing, exploratory data analysis (EDA), and feature transformation.

---

## 📁 Dataset

The dataset used is `housing.csv`, based on the California Housing Dataset. It contains the following features:

- `longitude`, `latitude`
- `housing_median_age`
- `total_rooms`, `total_bedrooms`
- `population`, `households`
- `median_income`
- `median_house_value` (target)
- `ocean_proximity` (categorical, removed in preprocessing)

---

## 📈 Results

- Categorical column `ocean_proximity` was removed to simplify numerical analysis.
- All missing values were successfully removed from the dataset using `dropna()`.
- Histograms and correlation analysis revealed insights about feature distributions.
- Strongest correlation with housing prices was found in `median_income`.
- Log transformation was applied to skewed features (`total_rooms`, `total_bedrooms`, `population`, `households`) for normalization.
- Data was split into training and testing sets to prepare for machine learning modeling.