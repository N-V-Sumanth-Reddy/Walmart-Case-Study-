# Walmart Customer Purchase Data Analysis

## Overview

This project performs statistical analysis on customer purchase data, with a focus on understanding patterns related to **age**, **marital status**, and **gender**. The analysis involves hypothesis testing, confidence interval calculations, and the use of the Central Limit Theorem (CLT) to estimate population parameters. Based on these insights, marketing strategies and recommendations are provided, making this analysis particularly beneficial for **small business owners** looking to optimize their customer targeting and marketing efforts.

---

## Table of Contents

- [Project Description](#project-description)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Author Information](#author-information)

---

## Project Description

This notebook uses **Walmart customer purchase data** to explore and analyze purchasing behaviors based on customer demographics. We apply statistical techniques such as hypothesis testing, confidence intervals, and the Central Limit Theorem (CLT) to derive meaningful insights about the target customer segments.

The results are presented in the form of detailed insights, including:
- Confidence intervals for various demographic groups.
- Comparison of purchase behavior between different segments (e.g., age groups, marital status, and gender).
- Practical recommendations for marketing campaigns based on observed patterns in the data.

This analysis can be highly beneficial for **small business owners** aiming to understand customer behaviors and optimize their marketing strategies.

---

## Data Analysis

### Key Components of the Analysis:
- **Confidence Interval Calculation**: 
  - We calculated confidence intervals for various age groups, gender, and marital status, providing insights into the expected purchase behavior for each segment.
  
- **Hypothesis Testing**:
  - We conducted hypothesis tests to compare the spending behavior between different customer groups (e.g., male vs. female, married vs. unmarried).
  
- **Central Limit Theorem (CLT)**:
  - The CLT was used to estimate population means and standard errors for male and female customers, as well as married and unmarried customers, for various sample sizes.
  
- **Segmentation**:
  - The analysis focused on segmenting customers based on demographics (age, marital status, gender) and analyzing their spending behavior.

---

## Insights

Based on the statistical analysis, the following key insights were derived:

- **Overlapping Confidence Intervals**: 
  - Confidence intervals for male and female customers, as well as for married and unmarried customers, showed no significant statistical difference in spending patterns.
  
- **Age Groups**:
  - For certain age groups (18-25 & 46-50; 36-45 & 55+), the confidence intervals overlapped, indicating similar spending behaviors. However, there were significant differences for other age groups (0-17, 26-35, 51-55).

- **Spending Behavior**:
  - Based on the statistical results, the **median** and **confidence intervals** indicate that customer spending behavior doesn't vary significantly across marital status and gender, but specific age groups show marked differences.

---

## Recommendations

### For Overlapping Age Groups (18-25 & 46-50; 36-45 & 55+):
- **Unified Campaigns**: Create unified marketing campaigns that address the common interests and spending behaviors of these overlapping age groups.
- **Standard Offers**: Implement promotions or discounts that appeal to both overlapping groups without needing to differentiate between them.

### For Non-Overlapping Age Groups (0-17, 26-35, 51-55):
- **Segment-Specific Promotions**: Develop targeted marketing strategies for each of these age groups, such as tailored promotions and offers.
- **Product Focus**: Adjust inventory and product offerings to align with the distinct needs and interests of these non-overlapping age groups.

### For Married and Unmarried Customers:
- **General Promotions**: Implement marketing strategies that target both groups equally since no significant difference in spending behavior was found.
- **Broad Offers**: Create broad promotions that appeal to all customers without distinguishing between marital status.

### For Male and Female Customers:
- **Segmented Campaigns**: Design campaigns that cater to the spending habits of each gender. For male customers, focus on high-value promotions, while for female customers, offer incentives to increase purchase amounts.

---

## Technologies Used

- **Python**: For data analysis and statistical calculations.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical calculations and statistical functions.
- **Matplotlib**: For creating visualizations and graphs.
- **SciPy**: For performing statistical hypothesis testing and confidence interval calculations.

---



### Prerequisites:
- Python 3
- Pandas
- NumPy 
- Matplotlib
- SciPy


Download or clone the repository.
Open the Jupyter notebook or Google Colab.
Run each cell to see the analysis and results.
## Author Information
- **Author**: Sumanth Reddy
- **Email**: sumanthreddy996@gmail.com
- **GitHub**: [github.com/sumanthreddy](https://github.com/N-V-Sumanth-Reddy?tab=repositories)
