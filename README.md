# 📊 Lead Scoring & Conversion Prediction Model

## 📌 Project Overview
This project focuses on building a **Lead Scoring Model** for an education company to predict the likelihood of lead conversion. Using historical lead interaction data, a **Logistic Regression** model is developed to assign a **conversion probability score (0–100)** to each lead, enabling the sales team to prioritize high-potential prospects.

---

## 🎯 Business Objective
- Improve lead-to-sale conversion efficiency  
- Reduce manual effort by prioritizing high-quality leads  
- Support data-driven decision-making for sales strategies  

---

## 🧠 Solution Approach
1. **Data Understanding & Cleaning**
   - Handled missing values and inconsistent entries  
   - Dropped irrelevant and high-null columns  
   - Encoded categorical variables  

2. **Exploratory Data Analysis (EDA)**
   - Identified key features influencing conversion  
   - Analyzed lead sources, engagement metrics, and behavioral patterns  

3. **Model Building**
   - Implemented **Logistic Regression** for interpretability  
   - Predicted probability of conversion instead of binary output  
   - Converted probabilities into **Lead Scores (0–100)**  

4. **Model Evaluation**
   - Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC-AUC Curve  
   - Business-driven threshold tuning  

---

## 📈 Key Results
- Model effectively differentiates between converting and non-converting leads  
- High recall achieved to capture maximum potential customers  
- Adjustable threshold supports both **growth-focused** and **efficiency-focused** strategies  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Model:** Logistic Regression  
- **Evaluation Metrics:** ROC-AUC, Precision, Recall, F1-score  

---
