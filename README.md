# 🏠 Inca Tribe Housing Price Analysis

Welcome to the **Inca Tribe Housing Price Analysis** notebook! This project provides a comprehensive, end-to-end workflow for exploring, cleaning, engineering, and modeling real estate data to predict housing prices.

## 📊 Project Overview
- **Dataset:** Inca Tribe House Prices.csv
- **Goal:** Predict housing prices using robust data science and machine learning techniques.

## 🚀 Features & Workflow
- **Data Cleaning:**
  - Handles missing values and inconsistent entries (e.g., 'unknown', whitespace, case sensitivity).
  - Drops or imputes features based on missingness thresholds.
- **Feature Engineering:**
  - Groups and encodes categorical variables (e.g., 'Level' grouped into floor categories).
  - One-hot encoding for categorical features.
  - Scaling of numeric features using MinMaxScaler.
- **Exploratory Data Analysis:**
  - Visualizes distributions, outliers, and feature relationships.
  - Calculates and visualizes feature correlations (Pearson, eta-squared).
- **Outlier Removal:**
  - Removes outliers by type and level using the IQR method.
- **Modeling:**
  - Compares multiple regression models: Linear, Ridge, Huber, Random Forest, and more.
  - Uses sklearn Pipelines to prevent data leakage.
  - Evaluates models with metrics and visualizations.
- **Interpretability:**
  - Ranks features by importance and correlation strength.
  - Provides clear summaries and recommendations.

## 📈 Example Visualizations
- Correlation heatmaps
- Boxplots by property type and level
- Predicted vs. actual price scatter plots

## 🛠️ How to Use
1. **Open the notebook** `HousingPrice.ipynb` in VS Code or Jupyter.
2. **Run cells sequentially** to follow the workflow from data loading to model evaluation.
3. **Modify or extend** the analysis for your own data or modeling needs.

## 💡 Tips
- The notebook is modular—feel free to swap models, add new features, or try advanced techniques (e.g., cross-validation, hyperparameter tuning).
- All preprocessing is done with best practices to ensure robust, reproducible results.

## 📚 Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn

Install requirements with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

**Created with ❤️ by the Inca Tribe Data Science Team**
