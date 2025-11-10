 ## Project Overview

This project explores **workplace mental health** using data science techniques applied to the **Kaggle “Mental Health in Tech Survey” dataset**.  
Our goal is to identify factors affecting employee well-being and develop a predictive framework that can help organizations and policymakers detect early mental health risks.

Using machine learning models such as **Random Forest**, **XGBoost**, and a **Stacking Ensemble**, we predict mental health outcomes and generate an **Early Warning Index (EWI)** — a simple score indicating potential mental health risk.

The project further includes **interactive visual dashboards**, a **global EWI map**, and a **policy simulation** that demonstrates the potential impact of reducing workplace stressors like “work interference”.

---

##  Key Features

- **Data Cleaning & Preprocessing:**  
  Handling missing values, encoding categorical variables, and scaling numeric data.

- **Machine Learning Models:**  
  - Random Forest Classifier  
  - XGBoost Classifier  
  - Stacking Ensemble (Random Forest + XGBoost + Logistic Regression)

- **Evaluation Metrics:**  
  Confusion Matrix, Classification Report, Feature Importance, and Accuracy Comparison.

- **Early Warning Index (EWI):**  
  Converts model probabilities into a 0–100 scale for easy interpretation of mental health risk.

- **Interactive Dashboards:**  
  Plotly-based visualizations for:
  - EWI distribution  
  - EWI by gender  
  - Global mental health risk map  
  - KPI indicators and risk summaries  

- **Policy Simulation:**  
  Simulates a 20% reduction in “work interference” and measures the improvement in average EWI — showing how small workplace changes can improve well-being.
