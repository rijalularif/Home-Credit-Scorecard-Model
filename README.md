# Home Credit Indonesia Customer Loan Repayment Analysis

## Project Overview:

This project, undertaken by a data scientist intern at Home Credit Indonesia in collaboration with Rakamin Academy, aims to:

1. **Develop a Machine Learning Model:** This model will predict whether loan applicants are likely to experience repayment difficulties.
2. **Identify Ideal Customers:** By analyzing existing data, the project seeks to identify customer characteristics associated with a high likelihood of successful loan repayment.

## Business Insights:

- The data reveals a high concentration of customers employed as accountants. A targeted campaign to express appreciation to this group is recommended.
- While the percentage of successful repayments is high for HR staff, IT staff, and realty agents, the number of customers in these professions applying for loans is relatively low. Promotional efforts targeting these groups could be beneficial.

## Data Preprocessing:

1. Missing Value Handling: The project addresses missing data ("xna" values) by replacing them with appropriate strategies.

2. Feature Engineering: New features are created based on existing data, potentially influencing loan repayment behavior.

## Machine Learning Models:

Several machine learning models were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbor
5. Neural Network

## Model Selection:

Random Forest emerged as the best model based on its superior performance metrics (accuracy, roc, precision, recall, and F1-score).

## Recommendations:

1. **Targeted Marketing:** Implement a marketing campaign focused on attracting students, accountants, skilled technology professionals, and managers to consider applying for loans.
2. **Further Research:** Conduct additional research, such as surveys, to investigate the potential challenges faced by clients on maternity leave or those unemployed when considering cash loan contracts. This information can be used to guide future loan recommendations and improve approval rates for clients with these income types.
3. **Prioritize Customer Segment:** Identify clients aged 35-45 who have successfully repaid their loans as a priority target group for future lending opportunities.
