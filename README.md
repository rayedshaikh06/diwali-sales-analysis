# diwali-sales-analysis


## Project Overview

This project analyzes Diwali retail sales data to identify revenue trends, customer purchasing behavior, and product performance using Python-based exploratory data analysis.

## Business Objectives

- Identify the most valuable customer age segment driving revenue.
- Analyze regional performance to determine the highest revenue-contributing zones.
- Evaluate product category performance to identify primary revenue drivers.
- Assess purchasing behavior differences between married and unmarried customers.


## Dataset

- Source: (Mock dataset)
- Rows: (11251)
- Key Columns: 13 columns after data cleaning (User_ID, Gender, Age, Marital_Status, Occupation, Product_Category, Purchase, State, Zone)

## Tools Used

- Jupyter Notebook
- Python
- Pandas
- NumPy
- Matplotlib


## Analysis Performed

- Imported and configured essential Python libraries (Pandas, NumPy, Matplotlib, Seaborn)
- Loaded and explored dataset structure (shape, head, info, descriptive statistics)
- Performed data cleaning:
  - Removed unnecessary columns
  - Handled missing values
  - Dropped null records
  - Converted data types
- Conducted revenue analysis:
  - Total revenue, total orders, average spend per order
- Gender-based revenue analysis (including percentage contribution)
- Age segmentation using binning to identify revenue-driving age groups
- Order volume analysis by age group
- State-level revenue analysis (Top 10 states)
- Zone-wise revenue comparison
- Occupation-based revenue analysis (Top 10 occupations)
- Product category revenue analysis (Top categories)
- Gender vs Product Category revenue comparison
- Marital status analysis:
  - Revenue comparison
  - Order volume comparison
  - Average spend comparison
- Consolidated findings into strategic business insights and recommendations


## Key Insights

 - The 26–35 age group dominates the customer base and leads in both total revenue (₹4.28 Cr+) and order volume, establishing it as the core revenue-driving segment.
 - Revenue is geographically concentrated, with UP leading at ₹1.9 Cr, and strong contributions from Maharashtra, Karnataka, and Delhi, while the Central zone emerges as the highest-performing region at ₹4.16 Cr.
 - IT professionals generate the highest revenue among occupations, followed by Healthcare, Aviation, and Banking, indicating stronger purchasing power within high-income segments.
 - Food is the dominant product category across both genders, significantly outperforming others, with lifestyle categories such as Clothing, Electronics, and Footwear forming the next major contributors.
 - Gender-based purchasing behavior is largely similar, with minor differences in category preference (females leaning toward Footwear, males toward Electronics).
 - Unmarried customers contribute higher total revenue and order volume; however, average spend per order remains nearly identical across marital status, suggesting revenue differences are volume-driven rather than spending-intensity driven.

## Business Recommendations

- Focus marketing on 26–35 age segment.
- Strengthen Central zone operations due to dominant revenue contribution.
- Expand Food category offerings as it is the primary revenue driver.
- Target unmarried segment with retention campaigns due to higher order volume.

## Files in This Repository

- diwali_sales_analysis.ipynb – Complete exploratory data analysis notebook
- Diwali_Sales_Data.csv – Dataset used for analysis
- README.md – Project overview, insights, and business recommendations
