# 📉 Telco Customer Churn Prediction

This project analyzes customer churn data from a telecom company. The goal is to identify key patterns behind customer attrition and build a machine learning model to predict churn.

---

## 📌 Project Overview

**Problem:**  
Customer churn is a critical business problem for telecom providers. Predicting churn allows companies to proactively retain customers and reduce revenue loss.

**Solution:**  
- Perform detailed Exploratory Data Analysis (EDA)
- Uncover trends in churn behavior (contract, charges, payment, etc.)
- Build classification models to predict churn
- Visualize and report key business insights

---

## 📊 Dataset

- Source: [IBM Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- Rows: `7,043` customers  
- Features: Demographic, account, usage, and service data  
- Target: `Churn` (Yes/No)

---

## 🔍 EDA Highlights

- Customers with **month-to-month contracts** and **electronic checks** churn significantly more.
- **Higher monthly charges** and **shorter tenure** are strong churn indicators.
- A correlation heatmap and several bar/box plots were used to visualize feature relationships.

---

## 🤖 Models Used

| Model                | Goal                 |
|---------------------|----------------------|
| Logistic Regression | Baseline classifier  |
| Random Forest       | Tree-based ensemble  |
| XGBoost             | High-performance     |

Metrics used: Accuracy, Precision, Recall, F1-Score, ROC AUC

---

## 🛠️ Tech Stack

- Python 3.13
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn, xgboost
- SHAP
- Power BI

---

## 📁 Project Structure

📦 telco-churn-project/

├── data/ # Raw and cleaned datasets (gitignored)

├── notebooks/

│ ├── telco-churn-eda.ipynb # EDA, visualizations, insights

│ └── telco-churn-modeling.ipynb # Preprocessing, modeling, tuning, SHAP

├── models/
│ └── final_xgb_model.pkl # Saved tuned XGBoost model

├── reports/

│ └── telco-churn-report.ipynb

├── requirements.txt # Project dependencies

├── README.md

└── .gitignore


---

## 🚀 How to Run

1. Clone this repo  
2. Install dependencies with `pip install -r requirements.txt`  
3. Run `telco-churn-analysis.ipynb` in Jupyter  
4. Replace `data/` with your dataset if needed
3. Launch Jupyter Notebook:

``` bash
Copy
Edit
jupyter lab
Open the notebooks in the notebooks/ folder.

Explore EDA, run modeling cells, and view dashboards or export reports.



---


## 📬 Contact

Made with ❤️ by Mrtz90  
