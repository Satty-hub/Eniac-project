# Eniac-project for discount pricing strategy
Eniac data analysis using Pandas and Seaborn is used for visualization
In this project we analyzed Eniac’s discounting approach to evaluate its effectiveness in driving sales and maintaining brand value. Through a detailed study of pricing data, product sales, and revenue trends (especially for Apple products), we identify optimal discount ranges and make strategic recommendations for future promotions.

# Onjectives:
1. Analyze the data and aseess whether product discounts are beneficial for the company in the long term or not.
2. Indentify the best discount range to generate maximum revenue.
3. Analyze the data and indetify brand-wise performance, we mainly focused on Apple.
4. Provide the best recommendation and pricing strategy to clean their outdated products.

# Structure

Eniac-pricing-strategy/
├── Pandas/
│ └── discount_analysis.sql
├── Visualizations (Seaborn)/
│ ├── discount_vs_units.png
│ ├── revenue_trends.png
│ └── price_comparison.png
├── Data/
│ └── eniac_sales_data.csv
├── eniac_discount_report.pdf
└── README.md

# Key take out from the analysis:
Brand & Sales Overview: Apple products dominate in both sales and revenue generation specially tech products. Sales behavior significantly changed between 2017 and 2018, highlighting seasonal and market saturation effects.

# Discount Range Analysis: 
Discount Quartiles:
  - Q11: 9.09%  
  - Q2 (Median): 17.65%  
  - Q3: 28.59%  
  - Outliers: Begin above 35%
  - Optimal discount range: 20–35% for balancing volume and value.

# Discount vs Units Sold:
Products within the 20–35% discount range showed higher sales. Aggressive discounts (>35%) worked only in selected products (e.g., outdated items).

# Expected vs. Actual Revenue: 
A comparative revenue analysis on the top 10 Apple products showed discrepancies due to over-discounting or undervaluing.

# Strategic Recommendations:

1. We should provide the max discunt at 35–40%, beyond this, revenue gain flattens or reverses.
2. Use the discounts selectively to low-movement or outdated products.
3. Seasonal discount shows more effective, rather than spreading promotions across the year.
4. Retain quality branding — most revenues stem from high-end products like Apple, so brand value must remain uncompromised.

# Tools and technique Used
- SQL: For quering analyzing the data and calculating the discounts.
- Seaborn, Matplotlib, Python: Used for visualization


