# German Credit Risk Modeling

## 📌 Overview
This project builds an end-to-end machine learning pipeline to predict loan applicant credit risk using the **German Credit Dataset (UCI Repository)**.  
It demonstrates data preprocessing, exploratory analysis, feature engineering, model building, evaluation, and business insights.

---

## 📊 Dataset
- **Source:** [German Credit Data – UCI Repository](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))  
- **Size:** 1,000 loan applicants  
- **Features:** 20 attributes (numerical + categorical)  
- **Target:** Credit risk classification (`1 = Good`, `2 = Bad`)

---

## ⚙️ Project Workflow
1. **Data Loading & Understanding**  
   - Import dataset, assign column names, inspect structure.
2. **Preprocessing**  
   - Encode categorical variables, normalize numerical features, handle target labels.
3. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions, correlations, and risk drivers.
4. **Feature Engineering**  
   - Derived features such as *Credit Amount per Duration*.
5. **Model Building**  
   - Logistic Regression (baseline)  
   - Random Forest (advanced)  
   - Gradient Boosting (modern ensemble)
6. **Evaluation**  
   - Confusion matrix, ROC curve, ROC-AUC score.  
   - Comparison of models.
7. **Business Insights**  
   - Key drivers of default risk identified.  
   - Recommendations for financial institutions.

---

## 📈 Results
- **Random Forest ROC-AUC:** ~0.75 (outperformed baseline Logistic Regression).  
- **Key Predictors:** High loan-to-duration ratio, poor credit history, low savings.  
- **Business Application:** Helps banks flag high-risk applicants, adjust interest rates, and reduce default exposure.

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
- **Environment:** Jupyter Notebook

---


## 📂 Repository Structure
- German_Credit_Risk_Modeling.ipynb    # Main Problem
-  README.md                           # Project documentation


---

📌 Author

**Anupam Kumar Malakar**
MSc Statistics, IIT Kanpur

