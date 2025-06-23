# Credit Approval Classification for a Financial Cooperative

**Status:** Completed University Project

### Objective
This project addresses a real-world business problem by developing a machine learning model to automate the credit approval process for a financial cooperative. [cite_start]The primary goal was to replace a subjective, manual review system  [cite_start]with an objective, data-driven model to reduce the risk of non-performing loans. 

### Key Features & Methodology
* [cite_start]**Worked with a real-world, confidential dataset** obtained from the cooperative's internal database, which was fully anonymized to protect customer privacy. 
* [cite_start]Engineered a complete data pipeline including data cleaning, feature scaling (Min-Max Scaling) [cite: 346][cite_start], and correlation-based feature selection. 
* [cite_start]Trained and rigorously evaluated two powerful classification models: **Logistic Regression** and **XGBoost**. 
* [cite_start]Used **Stratified K-Fold Cross-Validation** to ensure the model's performance was stable and reliable across different subsets of the data. 
* [cite_start]Implemented techniques like `class_weight='balanced'` and `scale_pos_weight` to handle the natural class imbalance in the dataset. 

### Key Result
[cite_start]Both models performed exceptionally well, with **XGBoost achieving over 99% accuracy**.  [cite_start]The analysis concluded with a strategic recommendation based on the trade-off between XGBoost's high precision and Logistic Regression's superior recall. 

### Tech Stack
* [cite_start]**Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn 
* [cite_start]**Environment:** Google Colab 

### View the Project
The complete code, analysis, and visualizations are available in the Google Colab notebook.

➡️ **[View the full analysis in Google Colab](https://colab.research.google.com/drive/1idpDeAWx6ulYWky6n6w_JqWFLSaL_0Rg?usp=sharing)**
