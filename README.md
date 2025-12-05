# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, with fraudulent transactions representing less than 1% of the total data. The notebook includes steps for data exploration, preprocessing, visualization, model training, and evaluation.

---

## 📥 Dataset Download

You can download the dataset used in this project from Google Drive:

👉 **Download creditcard.csv:**  
https://drive.google.com/file/d/1vdmI8WGMX95SE15faRupqCndgmbjPOqz/view?usp=sharing

After downloading, place the CSV file in your project folder and ensure that the file path in the notebook matches the location where it is stored.

---

## 📁 Project Overview

### Key Steps in the Notebook
- **Data Loading & Exploration**
  - Data shape, info, missing values, statistical summary
- **Exploratory Data Analysis (EDA)**
  - Class distribution
  - Outlier fraction
  - Fraud vs non-fraud transaction analysis
  - Correlation heatmap visualization
- **Data Preprocessing**
  - Feature/label split (X and Y)
  - Data scaling (if applied)
- **Model Training**
  - Machine learning model(s) for fraud detection
- **Model Evaluation**
  - Confusion matrix
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC (if included)

---

## 📊 Dataset Information

- **Total Transactions:** 284,807  
- **Fraudulent Transactions:** 492  
- **Genuine Transactions:** 284,315  
- **Fraud Ratio:** ~0.17%  

### Features
- `Time`
- `V1` to `V28` (anonymized PCA components)
- `Amount`
- `Class` (0 = Non-Fraud, 1 = Fraud)

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone <https://github.com/LavanyaChowdam23/Creditcard_Fraud.git>
