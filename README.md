# 💳 Credit Card Default Prediction

## 📌 Project Overview

This project focuses on predicting whether a credit card customer is likely to **default on their payment in the next month** using machine learning techniques.

The dataset contains customer demographic information, credit limits, repayment history, bill amounts, and previous payment amounts. Machine learning models can be trained using these features to identify customers who may have a higher risk of defaulting.

---

## 🎯 Objectives

- Analyze credit card customer data.
- Perform data preprocessing and exploratory data analysis.
- Identify important factors related to credit card default.
- Build a machine learning model for default prediction.
- Evaluate the performance of the model using appropriate metrics.
- Predict whether a customer will default on their next payment.

---

## 📊 Dataset

The dataset contains:

- **30,000 records**
- **25 columns**
- Customer demographic information
- Credit limit information
- Repayment status
- Bill amounts
- Previous payment amounts
- Default payment status

### Important Features

| Feature | Description |
|---|---|
| `LIMIT_BAL` | Amount of credit given to the customer |
| `SEX` | Gender of the customer |
| `EDUCATION` | Education level |
| `MARRIAGE` | Marital status |
| `AGE` | Age of the customer |
| `PAY_0` | Repayment status in the latest month |
| `PAY_2` – `PAY_6` | Previous repayment statuses |
| `BILL_AMT1` – `BILL_AMT6` | Monthly bill amounts |
| `PAY_AMT1` – `PAY_AMT6` | Previous payment amounts |
| `default payment next month` | Target variable |

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Machine Learning Model
   ↓
Model Evaluation
   ↓
Credit Card Default Prediction
```

---

## 🔍 Exploratory Data Analysis

The dataset is analyzed to understand:

- Customer age distribution
- Credit limit distribution
- Education and marital status
- Repayment behavior
- Bill amount patterns
- Payment amount patterns
- Relationship between customer features and default status

Visualizations such as **histograms, count plots, box plots, and correlation heatmaps** can be used for analysis.

---

## 🤖 Machine Learning

The dataset can be divided into:

- **Features (X):** Customer and payment-related information
- **Target (y):** `default payment next month`

The data is then divided into training and testing sets.

Example models that can be used:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

The best-performing model can be selected based on evaluation metrics.

---

## 📈 Model Evaluation

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

For credit default prediction, **precision and recall** are particularly useful because correctly identifying customers at risk of default is important.

---

## 📁 Project Structure

```text
Credit-Card-Default-Prediction/
│
├── creditcard.csv
├── credit_card_default_prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Default-Prediction.git
```

Navigate to the project folder:

```bash
cd Credit-Card-Default-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## ▶️ How to Run

1. Download or clone this repository.
2. Open the Jupyter Notebook.
3. Make sure the dataset is in the project directory.
4. Run the notebook cells sequentially.
5. Analyze the model results and predictions.

---

## 💡 Key Insights

This project helps demonstrate how customer financial and repayment information can be used to identify potential credit card defaults.

The analysis can help understand the relationship between:

- Credit limit
- Age
- Repayment history
- Bill amounts
- Payment amounts
- Default behavior

---

## 🚀 Future Improvements

- Try advanced ensemble models.
- Perform hyperparameter tuning.
- Handle class imbalance using suitable techniques.
- Perform feature engineering.
- Deploy the model using Streamlit or Flask.
- Create an interactive dashboard for credit risk analysis.
