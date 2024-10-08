# TELCO-CUSTOMER-CHURN-DATA-ANALYSIS-
This project is a Python-based Exploratory Data Analysis (EDA) focused on telecom customer churn. It analyzes customer demographics and service usage to identify key factors contributing to churn. Using libraries like Pandas, Matplotlib, and Seaborn, the project explores data cleaning, visualizations, and insights into customer behavior.

Project Overview:
This project is a **Python-based Exploratory Data Analysis (EDA)** on a telecom customer churn dataset. The primary objective is to analyze customer demographics and service usage data to identify key factors that contribute to customer churn. The dataset contains information about customer tenure, monthly charges, and subscriptions to various telecom services, along with whether or not the customer has churned.

Key Objectives:
- Understand the distribution of churn across customer demographics.
- Analyze the impact of different service subscriptions (like Online Security, Streaming Services) on churn.
- Identify the role of monthly charges and tenure in predicting customer churn.
- Provide actionable insights and recommendations to reduce churn.

Project Structure:
1. Data Cleaning:
   - Handle missing values (e.g., imputation for `TotalCharges`).
   - Convert categorical variables into appropriate data types.

2. Data Exploration:
   - Generate summary statistics for numerical variables.
   - Visualize customer churn distribution using pie charts and count plots.
   - Create subplots for service-based churn analysis.

3. Service-Specific Analysis:
   - Evaluate churn rates for customers using or not using services like Online Security, Tech Support, Phone Services, and Streaming Services.
   - Identify customer groups that are most likely to churn based on service subscriptions.

4. Churn Insights:
   - Tenure and churn correlation analysis.
   - Price sensitivity and its role in churn.
   - Service-based churn rate comparisons.

5. Visualization:
   - Stacked bar charts and pie charts for visualizing churn distribution.
   - Subplots for each telecom service to show churn distribution by service usage.

Key Findings:
- **Churn Rate**: 26.54% of customers have churned, which is a significant portion of the customer base.
- **Tenure Impact**: Customers with tenure less than 20 months are at a higher risk of churning.
- **Service Subscriptions**: Lack of services such as Online Security and Tech Support increases churn rates.
- **Price Sensitivity**: Customers paying higher monthly charges are more likely to churn.

Technologies Used:
- **Python**: Main programming language for data analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For code development and presentation.

Conclusion:
The analysis highlights the importance of customer tenure, pricing models, and service subscriptions in reducing churn. Based on the insights, telecom companies can focus on improving retention strategies, particularly for new customers and those with higher monthly charges.
