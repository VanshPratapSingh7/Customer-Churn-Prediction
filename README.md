# 📊 Customer Churn Prediction Using Machine Learning

An end-to-end Machine Learning project that predicts whether a telecom customer is likely to leave the service (churn). The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction using multiple machine learning algorithms.

---

## 🚀 Project Overview

Customer retention is one of the biggest challenges for subscription-based businesses. This project aims to identify customers who are likely to churn by analyzing customer demographics, account information, service usage, and billing details.

The project follows the complete Machine Learning pipeline:

- Data Collection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Prediction & Business Insights

---

## 📂 Dataset

The project uses the **IBM Telco Customer Churn Dataset**, containing customer demographic information, account details, subscribed services, and billing information.

### Dataset Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Tech Support
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Churn (Target Variable)

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

---

## 📈 Exploratory Data Analysis (EDA)

The project includes:

- Missing Value Handling
- Data Cleaning
- Feature Encoding
- Data Visualization
- Correlation Analysis
- Class Distribution Analysis
- Contract-wise Churn Analysis
- Internet Service Analysis
- Monthly Charges Distribution
- Tenure Distribution

---

## 🤖 Machine Learning Models

Two supervised learning models were implemented and compared:

### 1. Logistic Regression

- Baseline classification model
- Good recall for identifying churn customers

### 2. Random Forest Classifier

- Ensemble learning algorithm
- Better overall prediction accuracy
- Handles non-linear relationships effectively

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|----------|-----------|--------|----------|----------|
| Logistic Regression | 70.7% | 49.0% | 72.6% | 58.5% | 0.795 |
| Random Forest | **73.3%** | **52.3%** | 69.8% | **59.8%** | **0.795** |

---

## 📌 Key Insights

- Month-to-Month contracts have the highest churn rate.
- Customers using Fiber Optic Internet tend to churn more frequently.
- Customers with longer tenure are less likely to leave.
- Contract type and monthly charges significantly influence churn prediction.
- Random Forest achieved the best overall performance.


## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Customer_Churn_Prediction.ipynb
```

and run all cells.

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
plotly
scikit-learn
```

---

## 📈 Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Hyperparameter Tuning
- Deep Learning Models
- Model Deployment using Flask/FastAPI
- Streamlit Dashboard
- Docker Deployment

---

## 🎯 Business Benefits

- Early identification of customers at risk of churn
- Improved customer retention strategies
- Reduced revenue loss
- Better marketing decision-making
- Data-driven business insights

---

## 👨‍💻 Author

**Vansh Pratap Singh**

MCA (Hons.) – Data Science

Lovely Professional University

---

## ⭐ If you found this project helpful, consider giving it a Star!
