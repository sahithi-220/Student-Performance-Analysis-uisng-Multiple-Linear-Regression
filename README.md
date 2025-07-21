# 📊 Student Performance Predictor using Multiple Linear Regression

A machine learning project to predict student academic performance using Multiple Linear Regression based on academic and lifestyle-related factors. The model helps estimate a **Performance Index** to enable data-driven academic guidance and interventions.

---

## 📝 Project Overview

This project uses a structured dataset to analyze the impact of variables such as study hours, sleep time, exam scores, and extracurricular activities on student performance. The final model is evaluated using standard regression metrics and visualized with meaningful plots.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ✅ Core Highlights

- **📥 Multi-Feature Input**  
  Considers a mix of academic and lifestyle factors to improve prediction accuracy.

- **🧹 Comprehensive Preprocessing**  
  Categorical encoding, missing value handling, and scaling are performed for better model performance.

- **📈 Statistical Correlation Analysis**  
  Heatmaps and correlation matrices are used to identify key features influencing academic success.

- **📊 Model Evaluation Metrics**  
  - **R² Score** – Measures model fit  
  - **Mean Absolute Error (MAE)** – Average prediction error

- **📉 Intuitive Visualizations**  
  Plots such as scatter plots and heatmaps help visualize relationships and patterns in the data.

---

## 📂 Dataset Information

-[View Dataset](https://github.com/sahithi-220/Student-Performance-Analysis-uisng-Multiple-Linear-Regression/blob/main/Student_Performance.csv)

- **Target Variable**: `Performance Index`
- **Selected Features**:
  - Study Hours
  - Sleep Time
  - Previous Exam Scores
  - Extracurricular Activities
  - Practice of Sample Question Papers

---

## 🔁 Workflow Breakdown

1. **Loading & Cleaning Data**
   - Checked data types and cleaned null/missing values

2. **Encoding Categorical Fields**
   - Converted `Yes/No` responses in Extracurricular Activities to binary format

3. **Exploratory Data Analysis (EDA)**
   - Used scatter plots and histograms to understand data distribution

4. **Correlation Matrix & Feature Selection**
   - Plotted heatmap and selected top features based on correlation to target

5. **Feature Normalization**
   - Used `MinMaxScaler` to scale input features to 0–1 range

6. **Model Training**
   - Applied Multiple Linear Regression using `LinearRegression()` from Scikit-learn

7. **Performance Evaluation**
   - Used **R² Score** and **Mean Absolute Error (MAE)**

---

## 📈 Visual Output

- 🔹 **Scatter Plots**: Show trends between features and target
- 🔹 **Heatmap**: Highlights most influential variables via correlation
- 🔹 **Actual vs Predicted Plot** *(optional enhancement)*

---

## 🧪 Results Summary

- **R² Score**: *Varies based on test/train split but usually > 0.7*
- **MAE**: *Low error signifies reliable predictions*

---

## 🔮 Future Enhancements

- Try advanced models like **Polynomial Regression**, **Random Forest**, or **XGBoost**
- Add more features (e.g., socioeconomic status, family education background)
- Deploy as a web application using **Streamlit** or **Flask**
- Add cross-validation and hyperparameter tuning

---
