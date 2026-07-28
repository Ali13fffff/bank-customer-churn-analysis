## Project Steps

1. **Data Cleaning**
    - Removed unnecessary columns such as `RowNumber` and `CustomerId`.
    - Checked for missing values and duplicate records.
2. **Exploratory Data Analysis (EDA)**
    - Performed univariate and bivariate analysis to identify key churn drivers.
    - Compared balance, age, and product usage across churned vs. retained customers.
3. **Data Visualization**
    - Created visualizations to spot trends in Geography, Gender, and Age segments.

## 🔑 Key Insights & Business Recommendations

Our exploratory analysis highlighted several critical factors driving customer attrition:

* **Geographic Vulnerability:** Customers in **Germany** exhibit the highest churn rates, suggesting a potential localized service issue or a more competitive market environment.
* **High-Value Customer Loss:** Churn is not limited to low-activity accounts; customers with **high balances** are leaving. This is a critical threat to the bank's Assets Under Management (AUM).
* **Demographic Factors:** Older customers (**47-65+ years**) and **female customers** show higher churn propensities, indicating current retention strategies may be less effective for these specific segments.
* **Product Complexity:** A strong correlation exists between holding **3+ products** and high churn rates, suggesting potential service friction or product bundling issues.

**Strategic Business Recommendations:**
* **Localized Retention:** Implement targeted loyalty programs specifically for the high-risk German market.
* **Win-Back Campaigns:** Leverage the cluster of customers with **$0 balances** in France and Spain for low-cost reactivation campaigns.
* **Product Review:** Investigate why multi-product users (3+ products) are churning at higher rates to improve service quality.

## Future Work
* Perform data preprocessing for machine learning (encoding, scaling, and feature engineering).
* Train classification models such as **Random Forest** and **XGBoost**.
* Evaluate model performance using metrics like Accuracy, Precision, Recall, and F1-score.
