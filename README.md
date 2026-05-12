# 💳 Credit Card Fraud Detection Analysis ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 🚀 Machine Learning Project for Detecting Fraudulent Credit Card Transactions

Detecting fraudulent financial transactions using **Machine Learning**, **EDA**, **Data Visualization**, and **Classification Algorithms** on highly imbalanced datasets.

</div>

---

# 📌 Project Overview

Financial fraud detection is one of the most important real-world applications of Machine Learning.  
This project focuses on building a complete fraud detection pipeline capable of identifying suspicious credit card transactions efficiently.

The project includes:

✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Feature Understanding  
✔ Handling Imbalanced Data  
✔ Model Training & Evaluation  
✔ Hyperparameter Tuning  
✔ Fraud Prediction System  
✔ Model Serialization using Joblib  

---

# 🗂️ Project Structure

```bash
CREDIT-CARD-FRAUD-DETECTION/
│
├── 📁 models/
│   └── best_random_forest_model.pkl
│
├── 📁 Sample_data_Set/
│   ├── creditcard_sample.csv
│   └── data_set_link.txt
│
├── 📁 train_test_data/
│   ├── x_train.pkl
│   ├── x_test.pkl
│   ├── y_train.pkl
│   └── y_test.pkl
│
├── 📄 Credit_Card_Fraud_Detection.ipynb
├── 📄 model_evaluation.ipynb
├── 📄 .gitignore
└── 📄 README.md
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Joblib | Model Saving & Loading |

---

# 📊 Exploratory Data Analysis (EDA)

Extensive Exploratory Data Analysis was performed to understand transaction patterns and fraud behavior.

### 🔍 EDA Includes

- Missing Value Analysis
- Duplicate Detection
- Fraud vs Non-Fraud Distribution
- Correlation Analysis
- Transaction Amount Analysis
- Class Imbalance Analysis

---

# 📈 Visualizations

The project includes multiple visualizations such as:

✅ Fraud vs Non-Fraud Countplot  
✅ Transaction Amount Distribution  
✅ Transaction Time Distribution  
✅ Boxplots by Transaction Class  
✅ Correlation Heatmaps  
✅ Confusion Matrix Visualizations  

---

# ⚠️ Dataset Imbalance

One of the major challenges in fraud detection is the highly imbalanced dataset.

## Key Insight

> Fraudulent transactions are extremely rare compared to legitimate transactions.

Approximately:

```text
1 Fraudulent Transaction : 576 Legitimate Transactions
```

This project uses proper evaluation metrics and validation strategies to handle imbalance effectively.

---

# 🤖 Machine Learning Models

The following models were implemented and evaluated:

| Model | Status |
|---|---|
| Decision Tree Classifier | ✅ Tested |
| Random Forest Classifier | ✅ Best Performance |
| HistGradientBoosting Classifier | ✅ Tested |

---

# 🏆 Best Performing Model

## ✅ Random Forest Classifier

The Random Forest model achieved the best overall performance.

### Techniques Used

- Stratified K-Fold Cross Validation
- RandomizedSearchCV
- Hyperparameter Optimization
- Average Precision Scoring

---

# 📌 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- PR AUC Score
- Average Precision Score

---

# 💾 Model Serialization

The trained model was saved using **Joblib** for future predictions.

```python
joblib.dump(best_rfc, "best_random_forest_model.pkl")
```

---

# 🔮 Fraud Prediction System

A custom prediction function was implemented to classify transactions as:

- ✅ Legitimate Transaction
- 🚨 Fraudulent Transaction

```python
predict_class(input_data)
```

---

# ▶️ Installation & Usage

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/CREDIT-CARD-FRAUD-DETECTION.git
```

---

## 2️⃣ Navigate to Project

```bash
cd CREDIT-CARD-FRAUD-DETECTION
```

---

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Credit_Card_Fraud_Detection.ipynb
```

---

# 📚 Dataset Information

## Dataset Features

- Time
- Amount
- Class
- PCA Transformed Features (V1 → V28)

## Target Variable

| Class | Meaning |
|---|---|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

---

# 🚀 Future Improvements

Planned future enhancements:

- 🌐 Flask/FastAPI Deployment
- 📊 Streamlit Dashboard
- ⚡ Real-Time Fraud Detection API
- 🔍 Advanced Ensemble Models
- ☁ Cloud Deployment
- 📱 Interactive Frontend

---

# 📷 Sample Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
EDA & Visualization
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Fraud Prediction
```

---

# 👨‍💻 Author

## Dilshan Nethmin

💡 Machine Learning Enthusiast  
💻 Full Stack Developer  
📊 Data Analytics & AI Projects  

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🛠️ Contribute to improvements  

---

<div align="center">

## 🚀 Thanks for Visiting

### 💳 Credit Card Fraud Detection using Machine Learning

</div>
