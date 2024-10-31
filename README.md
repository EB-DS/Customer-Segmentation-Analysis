# Unveiling Consumer Insights: A Customer Segmentation Analysis

### Customer Retention Analysis and Modeling to Predict Customer Churn

## Overview
In today's competitive market, understanding customer behavior is crucial for businesses to effectively tailor their products and marketing strategies. Customer segmentation is a powerful data analysis technique that divides a company's customer base into distinct groups based on shared characteristics. This project is particularly impactful in industries such as retail, e-commerce, finance, and hospitality, where understanding and catering to diverse customer needs can significantly influence profitability and customer loyalty.

## Learning Objectives
This project serves as a practical introduction for students, with the following learning objectives:
1. **Understanding clustering algorithms** and their applications in real-world scenarios.
2. **Applying feature engineering** techniques to prepare and enhance datasets for analysis.
3. **Gaining proficiency in data visualization** to communicate insights effectively.
4. **Developing hands-on experience** in customer data analysis, including segmentation and profiling.

## Table of Contents
- [Overview](#overview)
- [Learning Objectives](#learning-objectives)
- [Data Source](#data-source)
- [Key Findings](#key-findings)
- [Modeling Insights](#modeling-insights)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [License](#license)
- [Further Reading](#further-reading)

## Data Source
The dataset used in this analysis, **Customer Segmentation Data for Marketing Analysis**, is publicly available on Kaggle. It contains information about customer demographics, account details, and service usage.

## Key Findings
- **Customer Tenure**: Customers with shorter tenures are at a higher risk of churning, suggesting that new customers may benefit from early engagement initiatives.
- **Monthly Charges**: Higher monthly charges are associated with increased churn, indicating pricing sensitivity among customers.
- **Contract Type and Payment Methods**: Month-to-month contracts and electronic checks are correlated with higher churn rates, highlighting opportunities for loyalty incentives and alternative payment options.

## Modeling Insights
- **Best Model**: The Random Forest model demonstrated an accuracy of 81% and an F1-score of 73% after hyperparameter tuning, making it effective in predicting churn.
- **Key Predictors**: The top predictors of churn were MonthlyCharges, TotalCharges, and tenure, which provide actionable insights for retention strategies.
- **Improvement Opportunities**: The model's performance can be further enhanced by testing additional algorithms, refining features, or adjusting hyperparameters.

## Requirements
To run this project, you'll need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the requirements using:
```bash
pip install -r requirements.txt
```

## Project Structure
Customer_Segmentation_Analysis.ipynb: Jupyter notebook containing the full analysis and modeling process.
Customer_Segmentation_Analysis.html: HTML report for easy viewing of the notebook.
customer_segmentation_data.csv: The dataset used for the project.
README.md: Project description and details.
LICENSE: License file for the project.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Further Reading
For more insights into customer segmentation and clustering, consider exploring the following resources:

- Wind, Y., & Cardozo, R. N. (1974). Market segmentation: A review. European Journal of Marketing, 8(1), 12-25.
- Punj, G., & Stewart, D. W. (1983). Cluster analysis in marketing research: Review and suggestions for application. Journal of Marketing Research, 20(2), 134-148.
- Wedel, M., & Kamakura, W. A. (2000). Market segmentation: How to do it and how to profit from it. Springer.
- Collica, R. S. (2011). Customer segmentation and clustering using SAS Enterprise Miner. SAS Institute.
















