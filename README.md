# ✈️ Airline Passenger Satisfaction Prediction using XGBoost

## 🧠 Overview
This project focuses on using machine learning techniques to predict airline passenger satisfaction.  
By leveraging the **XGBoost algorithm**, we aim to build a robust model that can accurately classify passengers as *Satisfied* or *Dissatisfied* based on various features such as flight distance, seat comfort, inflight service, and overall service quality.

---

## 🎯 Objectives
- Explore and preprocess the airline passenger satisfaction dataset.  
- Identify the most influential factors affecting satisfaction.  
- Train and tune an **XGBoost classifier** for optimal performance.  
- Evaluate model performance using accuracy, precision, recall, and F1-score.  
- Provide insights into customer satisfaction drivers using feature importance analysis.

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading & Exploration
- Load dataset using `pandas`
- Check dataset structure, null values, and summary statistics
- Visualize patterns and relationships using `matplotlib` and `seaborn`

### 2️⃣ Data Preprocessing
- Encode categorical variables (e.g., Gender, Customer Type)
- Scale numerical features if needed
- Split data into training and testing sets

### 3️⃣ Model Building
- Train an **XGBoostClassifier** using preprocessed data  
- Perform hyperparameter tuning to improve performance  

### 4️⃣ Model Evaluation
- Evaluate using:
  - Confusion Matrix  
  - Classification Report  
  - ROC-AUC Curve  

### 5️⃣ Feature Importance & Insights
- Plot feature importance using XGBoost’s built-in feature importance function  
- Identify key factors influencing passenger satisfaction  

---

## 🧰 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  
- **Notebook Environment:** Jupyter Notebook (`.ipynb`)

---

## 📊 Results
- Achieved strong predictive accuracy on test data  
- Identified major satisfaction drivers such as inflight service, seat comfort, and cleanliness  
- Provided actionable insights for improving airline customer experience  
