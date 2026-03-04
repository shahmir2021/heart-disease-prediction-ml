# ❤️ Heart Disease Prediction using Machine Learning

An end-to-end machine learning project that predicts the likelihood of heart disease using clinical patient data. This project demonstrates the full data science workflow including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

---

# 📊 Project Overview

Heart disease is one of the leading causes of death globally. Early detection using clinical data can help identify high-risk patients and support preventative healthcare decisions.

This project applies machine learning techniques to predict whether a patient is likely to have heart disease based on medical attributes such as age, cholesterol levels, blood pressure, and heart rate.

The project is divided into two major stages:

1. **Data preprocessing and exploratory analysis**
2. **Machine learning model training and evaluation**

---

# 🎯 Project Objectives

• Explore relationships between patient health indicators and heart disease  
• Identify the most important predictors of cardiovascular risk  
• Train machine learning models to classify heart disease presence  
• Evaluate model performance using classification metrics  
• Demonstrate a complete machine learning pipeline

---

# 🗂 Dataset

The dataset contains clinical patient health attributes commonly used for cardiovascular diagnosis.

| Feature | Description |
|------|------|
| Age | Age of the patient |
| Sex | Biological sex |
| Chest Pain Type | Type of chest pain experienced |
| Resting Blood Pressure | Blood pressure at rest |
| Cholesterol | Serum cholesterol level |
| Fasting Blood Sugar | Blood sugar level after fasting |
| Resting ECG | Electrocardiogram results |
| Max Heart Rate | Maximum heart rate achieved |
| Exercise Induced Angina | Chest pain during exercise |
| ST Depression | ST segment depression during exercise |
| Slope | Slope of peak exercise ST segment |
| Number of Major Vessels | Number of major blood vessels |
| Thalassemia | Blood disorder indicator |

Target variable:

```
1 = Heart disease present  
0 = No heart disease
```

---

# ⚙️ Project Workflow

## 1️⃣ Data Cleaning & Preprocessing

The dataset was prepared for modelling through several preprocessing steps:

- Handling missing values
- Removing duplicate entries
- Converting categorical variables
- Feature scaling and normalization
- Data type corrections

Exploratory data analysis was conducted to understand feature distributions and relationships.

---

## 2️⃣ Exploratory Data Analysis

EDA was performed to identify key patterns and correlations in the dataset.

Analysis included:

- Distribution of health indicators
- Correlation heatmaps
- Feature relationships with heart disease
- Identification of potential predictive variables

---

## 3️⃣ Machine Learning Models

Multiple classification algorithms were tested to predict heart disease risk.

Models implemented include:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 4️⃣ Model Evaluation

Model performance was evaluated using standard classification metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The models were compared to determine which algorithm performed best on the dataset.

---

# 📄 Project Reports

This project includes two detailed reports covering the full machine learning pipeline.

### 1️⃣ Data Preprocessing & Exploratory Analysis

This report includes:

- Data cleaning procedures
- Feature engineering
- Exploratory data analysis
- Dataset preparation for modelling

File:

```
heart_disease_data_preprocessing.pdf
```

---

### 2️⃣ Model Training & Evaluation

This report includes:

- Machine learning model training
- Model comparison
- Evaluation metrics
- Model performance analysis

File:

```
heart_disease_model_training_evaluation.pdf
```

---

# 🧰 Tools & Technologies

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

# 📁 Repository Structure

```
heart-disease-prediction-ml
│
├── heart_disease_analysis.ipynb
├── heart_disease_data_preprocessing.pdf
├── heart_disease_model_training_evaluation.pdf
├── dataset.csv
└── README.md
```

---

# 🔍 Key Insights

- Certain chest pain types are strongly associated with heart disease risk.
- Cholesterol and maximum heart rate show meaningful correlations with cardiovascular conditions.
- Machine learning models can effectively predict heart disease using standard clinical attributes.
- Ensemble models such as Random Forest often provide strong predictive performance.

---

# 🚀 Future Improvements

Potential extensions for this project include:

- Hyperparameter tuning for improved model performance
- Cross-validation for more robust evaluation
- Feature importance analysis
- Deployment of the model as a web application

---

# 👨‍💻 Author

**Shahmir Ayub**

MSc Applied Data Science (Distinction)  
Data Analyst | SQL | Python | Machine Learning
