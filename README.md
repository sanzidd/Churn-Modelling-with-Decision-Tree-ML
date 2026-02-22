# 🌳 Customer Churn Prediction with Decision Tree

A machine learning project that predicts customer churn for a bank using a Decision Tree classifier. Built as part of my hands-on ML practice to understand classification algorithms, data preprocessing, and model evaluation.

---

## 📌 Project Overview

Customer churn — when a customer stops using a service — is a critical problem for businesses. In this project, I use a **Decision Tree classifier** to predict whether a bank customer is likely to leave based on features like credit score, geography, age, balance, and more.

---

## 📂 Repository Structure

```
Churn-Modelling-with-Decision-Tree-ML/
│
├── Churn Modelling with Decision Tree..ipynb   # Main Jupyter Notebook
├── Churn_Modelling.csv                         # Dataset
└── README.md                                   # Project documentation
```

---

## 📊 Dataset

The dataset (`Churn_Modelling.csv`) contains **10,000 bank customer records** with the following key features:

| Feature | Description |
|---|---|
| `CreditScore` | Customer's credit score |
| `Geography` | Country (France, Germany, Spain) |
| `Gender` | Male / Female |
| `Age` | Customer's age |
| `Tenure` | Years as a customer |
| `Balance` | Account balance |
| `NumOfProducts` | Number of bank products used |
| `HasCrCard` | Whether the customer has a credit card |
| `IsActiveMember` | Whether the customer is active |
| `EstimatedSalary` | Estimated annual salary |
| `Exited` | **Target variable** — 1 if churned, 0 if retained |

---

## 🔧 Tech Stack

- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas` — data manipulation
  - `numpy` — numerical operations
  - `scikit-learn` — model building & evaluation
  - `matplotlib` / `seaborn` — data visualization

---

## 🚀 Workflow

1. **Data Loading** — Import and inspect the dataset
2. **Exploratory Data Analysis (EDA)** — Understand distributions and correlations
3. **Data Preprocessing** — Handle categorical encoding, feature selection, train-test split
4. **Model Training** — Fit a Decision Tree Classifier
5. **Model Evaluation** — Assess performance using accuracy, confusion matrix, and classification report
6. **Visualization** — Plot the decision tree for interpretability

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sanzidd/Churn-Modelling-with-Decision-Tree-ML.git
   cd Churn-Modelling-with-Decision-Tree-ML
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook "Churn Modelling with Decision Tree..ipynb"
   ```

---

## 📈 Results

The Decision Tree model was trained and evaluated on the bank churn dataset. Key metrics include accuracy score, confusion matrix, and a full classification report — all available inside the notebook.

---

## 🎯 Key Learnings

- How to frame a binary classification problem
- Encoding categorical variables for ML models
- Splitting data into training and testing sets
- Training and interpreting a Decision Tree
- Evaluating model performance with standard metrics

---

## 🙋 About

This is a **practice project** built to strengthen my understanding of supervised machine learning. It's part of my ongoing journey into data science and ML.

Feel free to explore the notebook, suggest improvements, or fork it for your own learning!

---

## 📬 Connect

**GitHub:** [@sanzidd](https://github.com/sanzidd)
