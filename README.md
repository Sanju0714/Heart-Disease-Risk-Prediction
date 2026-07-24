# ❤️ Heart Disease Prediction Using Machine Learning

A machine learning project to predict the 10-year risk of Coronary Heart Disease (CHD) using the Framingham Heart Study dataset. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature selection, model building, evaluation, and model saving.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals identify high-risk patients and take preventive measures.

This project uses patient demographic, lifestyle, and clinical data from the **Framingham Heart Study** to predict whether a patient is likely to develop coronary heart disease within the next 10 years.

---

## 🎯 Problem Statement

Develop a machine learning model to predict whether a patient is likely to develop coronary heart disease (CHD) within the next 10 years based on patient health information.

---

## 📊 Dataset Information

- **Dataset:** Framingham Heart Study Dataset
- **Total Records:** 4,238
- **Total Features:** 16
- **Target Variable:** `TenYearCHD`

**Target Classes**
- **0** → No Heart Disease
- **1** → Heart Disease

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 🔄 Project Workflow

- Data Loading
- Data Understanding
- Missing Value Analysis
- Missing Value Imputation (Median)
- Outlier Detection
- Exploratory Data Analysis (EDA)
- Feature Scaling (StandardScaler)
- Feature Selection (SelectKBest)
- Train-Test Split
- Model Building
- Model Evaluation
- Model Saving

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Distribution Analysis
- Histograms
- Box Plots
- Count Plots
- Correlation Heatmap

---

## 🤖 Machine Learning Models

Three classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

---

## 🏆 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **86.1%** |
| Decision Tree | **77.4%** |
| Random Forest | **85.5%** |

**Best Performing Model:** Logistic Regression

---

## 📁 Project Structure

```
Heart-Disease-Prediction-ML/
│
├── Dataset/
│   └── framingham.csv
│
├── Notebook/
│   └── Heart_Disease_Prediction.ipynb
│
├── Model/
│   └── Heart_Disease_Prediction_Model.pkl
│
├── Images/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Handle Class Imbalance
- Model Deployment using Flask or Streamlit
- Explainable AI (SHAP/LIME)
- Improve Recall for Better Medical Predictions

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction-ML.git
```

### Navigate to the project directory

```bash
cd Heart-Disease-Prediction-ML
```

### Install the required packages

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Heart_Disease_Prediction.ipynb** and run all the cells.

---

## 👩‍💻 Author

**Sanjana**

B.Tech Computer Science Engineering

Machine Learning | Data Science | Artificial Intelligence

---

## ⭐ Support

If you found this project helpful, consider giving this repository a ⭐ on GitHub.
