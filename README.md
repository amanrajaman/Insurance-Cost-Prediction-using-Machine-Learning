# 🏥 Insurance Cost Prediction using Machine Learning

This project focuses on predicting individual medical insurance costs using demographic and lifestyle data.
It applies exploratory data analysis (EDA), feature engineering, and machine learning regression models
to estimate insurance charges accurately.

The project demonstrates a complete **data analysis + ML workflow**, suitable for Data Analyst
and entry-level Machine Learning roles.

---

## 📌 Problem Statement
Medical insurance costs vary significantly based on factors such as age, BMI, smoking habits,
and region. Accurately predicting insurance charges can help insurance companies with pricing
strategies and risk assessment.

---

## 🎯 Objectives
- Analyze factors influencing insurance charges
- Perform data cleaning and exploratory data analysis
- Build regression models to predict insurance cost
- Evaluate model performance using appropriate metrics

---

## 🗂️ Dataset
- Dataset contains demographic and health-related attributes
- Key features include:
  - Age
  - Sex
  - BMI
  - Number of children
  - Smoker status
  - Region
  - Insurance charges (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of numerical variables
- Impact of smoking and BMI on insurance charges
- Correlation analysis between features
- Visualization using Matplotlib and Seaborn

---

## 🧠 Model Building
- Data preprocessing and encoding of categorical variables
- Train-test split
- Regression models applied:
  - Linear Regression
  - (Optional extensions: Ridge, Lasso, Random Forest)

---

## 📊 Model Evaluation
- Performance evaluated using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/insurance-cost-prediction.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Open the notebook
jupyter notebook Insurance\ Cost\ Prediction.ipynb
```

---

## 📈 Results & Insights

- Smoking status is the most influential factor in insurance cost
- BMI and age significantly impact charges
- Regression model successfully captures cost trends

---

## 🔮 Future Improvements

- Add advanced regression models
- Perform hyperparameter tuning
- Deploy as a web application using Flask or FastAPI
- Convert notebook logic into reusable Python modules

---

📜 License

This project is licensed under the MIT License.
```bash

---

## 📁Repository Structure (For THIS Notebook)

```text
insurance-cost-prediction/
│
├── notebooks/
│   └── Insurance Cost Prediction.ipynb
│
├── data/
│   └── insurance.csv
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```
