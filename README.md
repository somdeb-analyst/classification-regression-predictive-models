# 🤖 Predictive Modeling Project: CPU Usage & Contraceptive Use Classification

This repository contains two real-world machine learning projects using **Linear Regression** and **Classification** models. Both were developed using Python, focusing on applying data preprocessing, model building, evaluation, and interpretation techniques for predictive analytics.

---

## 🧩 Project 1: Predicting CPU User-Mode Time (Linear Regression)

### 📄 Dataset
The **Comp-activ** dataset contains system activity metrics collected from a Sun Sparcstation 20/712. The system was used in a university setting, performing diverse tasks like web browsing, editing, or CPU-intensive computing.

### 🎯 Objective
Build a **linear regression model** to predict the percentage of CPU time spent in **user mode**, based on system parameters such as memory usage, system load, process queue size, and others.

### ✅ Key Steps
- Loaded and cleaned the dataset
- Performed exploratory data analysis (EDA)
- Standardized features
- Trained linear regression models (including regularized models)
- Evaluated performance using RMSE, R², and residual analysis
- Analyzed **feature importance** to interpret the most influential metrics

### 📈 Outcome
- Accurately predicted CPU user-mode time
- Identified key predictors such as memory usage and process queue size
- Provided insight into system performance metrics

---

## 🧩 Project 2: Predicting Contraceptive Use (Classification)

### 📄 Dataset
Survey conducted by the **Republic of Indonesia Ministry of Health** on 1473 women (not pregnant or unaware of pregnancy status). Includes socio-demographic characteristics such as age, education, number of children, occupation, and more.

### 🎯 Objective
Build a **classification model** to predict whether a woman uses **any contraceptive method** based on her background. This helps in identifying target groups for awareness programs.

### ✅ Key Steps
- Loaded and preprocessed the data
- Converted categorical variables
- Visualized distributions and correlations
- Trained and compared models: Logistic Regression, Decision Trees, Random Forest, KNN
- Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix

### 📈 Outcome
- Achieved good classification performance with balanced metrics
- Identified significant features like number of children, education level, and husband's occupation
- Suggested use in **targeted population control campaigns**

---

## 🛠️ Tools & Libraries

| Tool            | Purpose                            |
|------------------|-------------------------------------|
| Python           | Programming language               |
| Pandas & NumPy   | Data manipulation and computation  |
| Scikit-learn     | ML model training and evaluation   |
| Matplotlib/Seaborn| Data visualization                |
| Jupyter Notebook | Interactive development environment|

---

