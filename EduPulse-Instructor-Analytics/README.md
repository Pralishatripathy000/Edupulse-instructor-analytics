
# 📊 EduPulse

### AI-Powered Instructor Effectiveness Analytics

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Regressor-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-yellow)

Machine Learning project for predicting **course completion rates** using instructor and learner engagement metrics. EduPulse applies multiple regression algorithms to educational analytics data, compares model performance, and identifies the key factors influencing learner success.

---

## 🎯 Overview

Educational institutions generate large volumes of engagement data from learners and instructors. Transforming this data into actionable insights enables better academic planning, improved learner engagement, and early intervention strategies.

EduPulse analyzes educational engagement metrics to predict **course completion rate**, compares multiple machine learning models, and identifies the most influential features affecting learner outcomes.

---

## ✨ Features

- Comprehensive Exploratory Data Analysis
- Data Cleaning & Preprocessing
- Multiple Regression Models
- Model Performance Comparison
- Feature Importance Analysis
- Residual Analysis
- Model Persistence
- Prediction Report Generation
- Professional Project Structure

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains educational engagement metrics including:

- Completion Rate
- Average Quiz Score
- Dropout Rate
- Average Watch Time
- Assignment Submission Rate
- Feedback Response Rate
- Average Feedback Score
- Forum Activity Rate
- Score Improvement
- Instructor & Course Information

**Target Variable**

- Completion Rate

---

# 📈 Exploratory Data Analysis

The notebook includes:

- Missing Value Analysis
- Duplicate Record Detection
- Correlation Heatmap
- Distribution Analysis
- Boxplots
- Scatter Plots
- Feature Correlation Analysis

---

# 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| **Linear Regression** | **0.0392** | **0.0495** | **0.8999** |
| Gradient Boosting | 0.0408 | 0.0519 | 0.8899 |
| Random Forest | 0.0414 | 0.0520 | 0.8896 |
| XGBoost | 0.0446 | 0.0558 | 0.8727 |
| Decision Tree | 0.0533 | 0.0682 | 0.8102 |

---

# 🏆 Best Model

**Linear Regression**

Performance:

- **R² Score:** 0.8999
- **RMSE:** 0.0495
- **MAE:** 0.0392

Despite evaluating several ensemble models, Linear Regression achieved the highest predictive performance, indicating a predominantly linear relationship between educational engagement metrics and course completion rate.

---

# 📊 Feature Importance

The most influential features identified by the Linear Regression model include:

1. Average Watch Time
2. Average Quiz Score
3. Dropout Rate
4. Average Feedback Score
5. Average Score Improvement

These variables contribute most significantly toward predicting learner completion rates.

---

# 📁 Project Structure

```text
EduPulse-Instructor-Analytics/
│
├── data/
│   ├── raw/
│   │   └── instructor_effectiveness.csv
│   └── processed/
│       └── processed_instructor_effectiveness.csv
│
├── models/
│   └── best_model.pkl
│
├── notebooks/
│   └── EduPulse_Analysis.ipynb
│
├── outputs/
│   ├── figures/
│   │   ├── feature_importance.png
│   │   ├── model_comparison.png
│   │   └── residual_plot.png
│   │
│   └── reports/
│       ├── model_comparison.csv
│       └── predictions.csv
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 Installation

```bash
git clone https://github.com/Pralishatripathy000/EduPulse-Instructor-Analytics.git

cd EduPulse-Instructor-Analytics

pip install -r requirements.txt

jupyter notebook
```

---

# 📌 Results

The project successfully demonstrates that educational engagement metrics can accurately predict learner completion rates.

The trained model achieved nearly **90% explanatory power (R² = 0.8999)**, highlighting the effectiveness of data-driven educational analytics.

---

# 🔮 Future Scope

- Real-time educational analytics dashboard
- REST API deployment
- Explainable AI using SHAP/LIME
- Deep Learning approaches
- Student risk prediction
- Instructor performance monitoring

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Pralisha Tripathy**

Engineering Student • Data Science • Machine Learning • AI

If you found this project interesting, consider giving it a ⭐.
