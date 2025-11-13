#  HRMIS Predictive Analytics System

###  Business & Technical Project Overview

The **HRMIS Predictive Analytics System** is a machine learning project designed to help HR departments identify and manage employee attrition risks using data-driven insights.  
It provides HR managers with **predictive models**, **visual insights**, and **decision support tools** to reduce turnover and improve employee retention strategies.

---

##  Project Objectives

- Predict employee **attrition likelihood** using HR data.  
- Identify **key drivers** that influence employee turnover.  
- Enable **data-driven HR decisions** on engagement, training, and workforce planning.  
- Provide **automated analytics** and insights through an integrated HRMIS system.

---

##  Features

Synthetic HR dataset generation (departmental attrition rates, salary, tenure, etc.)  
 End-to-end machine learning pipeline (preprocessing → training → evaluation)  
 Data balancing using **SMOTE** to handle class imbalance  
 Model comparison using **Random Forest**, **Logistic Regression**, and **XGBoost**  
 Visualization of attrition trends and model performance  
 Explainability through **feature importance analysis**

---

##  Technical Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| Data Analysis | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn, imbalanced-learn, xgboost |
| Notebook Environment | Jupyter Notebook |
| Model Evaluation | Accuracy, F1-Score, Balanced Accuracy, Confusion Matrix |

---

##  Project Workflow

1. **Data Generation / Loading**  
   Synthetic HR dataset is generated with key HR metrics (age, department, salary, satisfaction, etc.).

2. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize / scale features  
   - Split into train/test sets  

3. **Data Balancing**  
   - Apply **SMOTE** to handle imbalance between “Attrition: Yes” and “No” classes  

4. **Model Training**  
   - Random Forest  
   - Logistic Regression  
   - XGBoost  

5. **Model Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1, Balanced Accuracy  
   - Visuals: Confusion Matrix, ROC Curve  

6. **Insights & Recommendations**  
   - Identify top attrition drivers  
   - Recommend HR policy changes  

---

##  Sample Insights

- Employees in **Sales** and **Marketing** departments show higher attrition rates.  
- **Job satisfaction**, **monthly income**, and **tenure** are top predictors.  
- SMOTE balancing improved minority class prediction 

---

