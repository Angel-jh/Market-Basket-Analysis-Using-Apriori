# Market Basket Analysis Using Apriori

## Overview
This project applies Market Basket Analysis (MBA) using the Apriori algorithm to analyze customer purchasing behavior in supermarket transactions. The objective is to identify product combinations that are frequently purchased together and transform the findings into actionable business insights.

The analysis helps businesses understand customer shopping patterns and supports data-driven strategies such as cross-selling, product bundling, store layout optimization, and inventory management.


## Objectives
- Identify frequent product combinations purchased together
- Discover association rules using Apriori
- Analyze customer purchasing behavior
- Generate business insights for marketing and sales strategies
- Visualize product relationships and transaction patterns


## Dataset
The dataset contains supermarket transaction records with approximately 9,835 transactions.

### Features:
- Member Number
- Date
- Item Description

Dataset Source:
Kaggle - Groceries Dataset for Market Basket Analysis


## Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- mlxtend


## Data Preprocessing
The dataset was cleaned and transformed before applying Apriori:

- Removed duplicate records
- Standardized column names
- Grouped transactions by customer
- Converted transaction data into one-hot encoded format
- Validated transaction structures


## Methodology
The Apriori algorithm was implemented using the `mlxtend` library to generate frequent itemsets and association rules.

### Metrics Used:
- Support
- Confidence
- Lift
- Leverage

### Selected Thresholds:
- Minimum Support: 0.003
- Minimum Confidence: 0.5
- Minimum Lift: 3


## Key Findings
Some strong purchasing patterns discovered include:

- Sliced cheese + waffles → yogurt + whole milk
- Dessert + red/blush wine → pastry
- Whole milk + rolls/buns → other vegetables

The analysis revealed strong associations between breakfast products, meal-prep items, and snack-related purchases.


## Visualizations
The project includes:
- Top purchased products bar chart
- Most frequent item pair analysis
- Support vs Confidence scatter plot
- Confidence vs Lift scatter plot
- Product co-occurrence heatmap


## Business Recommendations
Based on the findings, several business strategies were proposed:

- Product bundling
- Cross-selling recommendations
- Store layout optimization
- Promotional targeting
- Inventory management improvements


## Results
The Apriori analysis successfully identified meaningful and statistically significant purchasing patterns that can support business decision-making and improve operational efficiency.

---

## Author
Angelica Julie Herliman
