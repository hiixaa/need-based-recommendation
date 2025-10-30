# need-based-recommendation
A machine-learning based recommendation system for bank clients. Trains two classifiers using supervised learning to predict clients’ income and accumulation investment tendencies, then recommends suitable financial products based on their investment behavior and risk propensity.

##  Project Overview
- **Dataset:** `Needs.xls` — 5000 client samples with 7 features and 2 label columns:
  - `IncomeInvestment`
  - `AccumulationInvestment`
- **Goal:** Predict investment behavior and recommend appropriate financial products such as:
  - Balanced Mutual Fund  
  - Fixed Income Fund  
  - Long-Term Deposit Plan  

---
##  Approach
1. Data preprocessing and feature selection.  
2. Built two supervised learning models:
   - Model 1 → Predicts *IncomeInvestment*
   - Model 2 → Predicts *AccumulationInvestment*
3. Evaluated models using Logistic Regression and other classifiers.  
4. Combined both predictions with clients’ **Risk Propensity** to generate a final **investment recommendation**.

---

##  Technologies Used
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn (for visualization)  
- Jupyter Notebook  


