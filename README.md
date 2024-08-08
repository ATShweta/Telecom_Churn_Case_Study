# Telecom Churn Case Study
Predicting High-Value Customer Churn in the Telecom Industry Using Machine Learning and Dimensionality Reduction Techniques

<hr>

### Problem Statement

In the highly competitive telecom industry, customer churn is a significant issue, with an annual churn rate of 15-25%. Retaining existing customers is more cost-effective than acquiring new ones, making customer retention a top priority for telecom operators. The business challenge is to predict which customers are at high risk of churn and identify the main indicators of churn, specifically focusing on high-value customers.

<hr>

### Objective

1. **Predictive Modeling:**
   - Build models to predict churn among high-value prepaid customers using customer-level data from a leading telecom firm.
   - Use the data from the first three months (June, July, August) to predict churn in the fourth month (September).
   - Identify high-risk customers in the "action" phase, allowing the company to take corrective actions to prevent churn.

2. **Feature Identification:**
   - Determine the key indicators that predict customer churn.
   - Use dimensionality reduction techniques like PCA and classification models to achieve the prediction goal.
   - Develop a separate model to identify important predictor variables, which will help understand the reasons behind customer churn.

3. **Business Insights:**
   - Provide actionable insights based on the predictive models and important features identified.
   - Recommend strategies for customer retention based on the analysis.

  <hr>
  
### **Algorithms and Techniques:**

1. Importing Necessary Libraries
2. Reading and Understanding the Dataset
3. Data Preprocessing
   - High Value Customer
   - Tagging Churn
4. Data Cleaning and EDA
   - Deriving New Features
5. Data Preparation
   - Standardization
   - Handling Class Imbalance
   - PCA
6. Model Building
   - Logistic Regression
     - RFE for Feature Selection
     - Plotting ROC
     - Top 10 predictors
    - Decision Tree
       - ROC curve
       - Hyperparameter Tuning
    - Random Forest
       - ROC curve
       - Hyperparameter Tuning
    - Adaboost
7. Conclusion
