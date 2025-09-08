# Liver Cirrhosis Prediction

This project applies **machine learning models** to predict the outcomes of patients with liver cirrhosis.  
The work involves handling class imbalance, hyperparameter tuning, and generating predictions on unseen test data.

---

---

## Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Normalized features

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and correlations
   - Plotted survival status across key features
   - Built interactive charts with Plotly

3. **Modeling**
   - Models applied:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Used **RandomizedSearchCV** for hyperparameter tuning
   - Applied **SMOTE** to handle class imbalance
   - Evaluated with **Stratified Cross-Validation**

4. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, and F1-score (per class)
   - Macro vs Weighted Averages

5. **Feature Importance**
   - Extracted important predictors using Random Forest and XGBoost
   - Visualized top features contributing to predictions

---

## Results

- **Random Forest (tuned with SMOTE):** Accuracy ~82%  
- **XGBoost (tuned with SMOTE):** Accuracy ~84%  
- Logistic Regression performed lower but gave insight into linear decision boundaries.

