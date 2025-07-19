# Week-4-Project-Predict-Employee-Attrition-using-Machine-Learning

# 🧠 Employee Attrition Prediction

This project uses machine learning to predict whether an employee will leave the company based on HR data. It's based on the IBM HR Analytics dataset.

## 📁 Dataset

- Source: [Kaggle – IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Contains employee details like age, job role, income, overtime, and attrition status.

## 🔧 Tools & Libraries

- Python
- pandas, matplotlib, seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- XGBoost

## 🚀 Workflow

### 1. Load and Explore Data
- Loaded the dataset using pandas.
- Explored shape, columns, and class imbalance in attrition.

### 2. Data Cleaning & Preprocessing
- Dropped irrelevant columns.
- One-hot encoded categorical features.
- Scaled numeric features.
- Balanced the data using SMOTE.

### 3. EDA (Exploratory Data Analysis)
- Visualized correlation heatmap, attrition distribution, and salary patterns.

### 4. Model Training
- Trained 3 models: Logistic Regression, Random Forest, and XGBoost.
- Used cross-validation for evaluation.

### 5. Evaluation
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
- Focused on **recall** to minimize false negatives.

### 6. Feature Importance
- Identified key features like `OverTime`, `MonthlyIncome`, and `YearsAtCompany`.

## ✅ Results

- **Best Model:** Random Forest  
- **Recall Score:** ~91%  
- Model helps HR predict and reduce employee attrition with real insights.

