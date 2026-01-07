# 🏦 predict-total-savings

This project applies machine learning to predict **total potential savings for customers** using a structured customer dataset. The project demonstrates skills in **data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling**.

---

## 📂 Project Structure

```
📁 predict-total-savings
│── data.csv/                                       # Customer dataset
│── Predicting_Potential_Savings_Total.ipynb/       # Jupyter notebooks for EDA and modeling
│── requirements.txt/                               # Libraries
│── README.md                                       # Project documentation
```

---

## 🔑 Key Stages

### 1. Data Processing
- Aggregated individual potential savings into a single target variable
- One-Hot Encoding for categorical variables
- Standard Scaling for numerical variables

### 2. Data Exploration (EDA)
- Analyzed feature distributions using histograms, scatter plots, countplots, and correlation heatmaps
- Investigated relationships between features and target variable

### 3. Modeling & Prediction
- Applied **XGBoost** and **Random Forest Regressor**
- Evaluated performance using **MAE, MSE, and R²**
- Hyperparameter tuning to optimize accuracy

---

## ⚙️ Tools & Libraries

- **Programming Language**: Python
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: XGBoost, Scikit-learn (RandomForestRegressor, hyperparameter tuning)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AykanIpek/predict-total-savings.git
   cd predict-total-savings
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook or Python scripts:
   ```bash
   jupyter notebook notebooks/Predicting  Potential Savings Total.ipynb
   ```

---

## 📊 Results

- **Models Used**: XGBoost, Random Forest Regressor
- **Performance Metrics**: MAE, MSE, R²
- **Outcome**: Accurate predictions of total potential customer savings

---

## 📌 Future Improvements

- Experiment with ensemble and boosting techniques for better performance
- Feature selection to reduce dimensionality
- Deploy model with a simple web dashboard (Flask/Streamlit)

---

📧 **Author**: AykanIpek  
