# Telecom-Customer-Churn-Analysis

This project analyzes customer churn for a telecom company to uncover key factors driving attrition and to provide actionable insights for customer retention. By leveraging data analysis and visualization, this project highlights the customer attributes most associated with churn, enabling the telecom company to prioritize strategies for reducing customer turnover.

## Project Overview

The project includes data preprocessing, exploratory data analysis, feature engineering, and visualization of customer attributes such as contract type, monthly charges, payment method, and demographics. With a focus on identifying high-risk segments, this analysis aims to inform strategies that can help retain customers and boost customer satisfaction.

## Key Findings

- **Churn Rate**: Approximately **26%** of customers have churned, signaling a significant area for improvement.
- **Contract Type**: Customers on month-to-month contracts exhibit a **42% churn rate**, much higher than those on one-year (**11%**) or two-year (**3%**) contracts.
- **Monthly Charges**: Higher monthly charges are correlated with increased churn. Customers paying over $70 per month have a **45% churn rate**, while those under $30 experience less than **10% churn**.
- **Senior Citizens**: Senior customers churn at a rate of **41%**, compared to **24%** for non-seniors, suggesting the need for targeted retention efforts.
- **Payment Method**: Customers using electronic checks show a **34% churn rate**, significantly higher than other payment methods (bank transfer at **17%**, credit card at **16%**, mailed check at **15%**).
- **Tenure**: Tenure is inversely related to churn; customers with less than 12 months have a **50% churn rate**, while those with over five years have less than **5% churn**.
- **Add-on Services**: Customers with multiple add-on services churn at a lower rate (**18%**) than those without (**30%**).

## Visualization

All visualizations are consistently color-coded in blue and pink to ensure uniformity across plots, aiding in the interpretation of insights.

## Installation

To get started with this project, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/TelecomChurnAnalysis.git
cd TelecomChurnAnalysis
pip install -r requirements.txt
```
## Executive Summary

The **Telecom Churn Analysis** project identifies primary churn drivers within the customer base, aiming to help the company reduce attrition through data-driven insights.

1. **Incentivize Long-Term Contracts**: Customers with longer contracts have much lower churn rates, suggesting a potential retention strategy.
2. **Focus on High Monthly Charges**: Customers paying over $70 per month churn at high rates, indicating the need for loyalty rewards or personalized offers to improve value perception.
3. **Target Senior Customers**: Senior citizens have high churn rates and may benefit from specialized plans or support services.
4. **Enhance Payment Options**: Electronic check users show the highest churn, highlighting the need to improve or offer alternative payment methods.

### Summary of Findings (Percentages)

- **Churn Rate**: 26%
- **By Contract Type**:
  - Month-to-Month: 42%
  - One-Year: 11%
  - Two-Year: 3%
- **By Monthly Charges**:
  - Above $70: 45%
  - Below $30: <10%
- **By Senior Citizen Status**:
  - Senior Citizens: 41%
  - Non-Senior: 24%
- **By Payment Method**:
  - Electronic Check: 34%
  - Bank Transfer: 17%
  - Credit Card: 16%
  - Mailed Check: 15%
- **By Tenure**:
  - Less than 12 Months: 50%
  - Over Five Years: <5%
- **By Add-on Services**:
  - Multiple Services: 18%
  - Minimal/No Add-ons: 30%
