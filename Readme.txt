Diwali Sales Data Analysis

## Project Overview
This project focuses on analyzing Diwali sales data to understand customer purchasing behavior and identify which customer segments contribute the most to total sales. The analysis explores spending patterns based on gender, age group, state, occupation, product category, and marital status.

The goal is to derive meaningful business insights that can help businesses understand their customers and make better marketing and sales decisions.

## Objectives
- Identify which gender contributes more to total sales.
- Analyze spending patterns across different age groups.
- Identify states contributing the most to sales.
- Understand purchasing behavior across occupations.
- Determine the most popular product categories by order count and total sales.
- Compare spending patterns between married and single customers.
- Identify customer segments with high purchasing activity.

## Dataset
- **Source:** [Diwali Sales Dataset on GitHub](https://github.com/Kalai865/Data_Analysis-Datasets)
- **File:** `sales_data.csv`
- **Original records:** 11,251
- **Original columns:** 15
- **Records after cleaning:** 11,239 rows before duplicate removal, followed by removal of 8 duplicate rows.
- **Final records:** 11,231 rows
- **Final columns:** 13

### Key Features
- `User_ID`: Customer identifier
- `Gender`: Customer gender
- `Age Group`: Customer age category
- `Age`: Customer age
- `Marital_Status`: Marital status
- `State`: Customer's state
- `Zone`: Geographical zone
- `Occupation`: Customer occupation
- `Product_Category`: Product category
- `Orders`: Number of orders
- `Amount`: Purchase amount

## Tools and Technologies
- **Python** – Data analysis
- **Google Colab** – Notebook development and execution
- **Pandas** – Data cleaning, manipulation, and grouping
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical charts and visualizations

## Data Cleaning and Preparation
The following data preparation steps were performed:

1. Loaded the CSV dataset using Pandas.
2. Examined the dataset structure, column names, and data types.
3. Identified missing values in the `Amount` column.
4. Removed the empty `Status` and `unnamed1` columns.
5. Removed rows containing missing values, resulting in 11,239 records.
6. Converted gender codes (`F` and `M`) into `Female` and `Male`.
7. Converted marital status codes (`0` and `1`) into `Single` and `Married`.
8. Identified and removed 8 duplicate rows.
9. Used grouping and aggregation to compare sales across customer segments.

## Exploratory Data Analysis
The analysis examined the following dimensions:

### 1. Gender Analysis
Compared the number of customers and total purchase amount for male and female customers.

### 2. Age Group Analysis
Analyzed customer counts and total sales across different age groups to identify high-value customer segments.

### 3. Marital Status Analysis
Compared the purchasing behavior and total spending of single and married customers.

### 4. State Analysis
Evaluated customer distribution and total sales across states to identify major sales-contributing regions.

### 5. Occupation Analysis
Compared customer counts and total purchase amounts across occupations, including IT, healthcare, aviation, and other sectors.

### 6. Product Category Analysis
Examined order counts and total purchase amounts across product categories to identify popular categories and major contributors to sales.

## Key Findings
Based on the visualizations and observations from this analysis:

- Female customers contribute more to total spending than male customers.
- Customers aged **26–35** are an important spending segment.
- Uttar Pradesh, Karnataka, and Maharashtra were identified in the analysis as significant states for customer spending.
- Customers working in IT, aviation, and healthcare were identified as relevant customer segments.
- Food, electronics, and clothing were observed as important product categories in the analysis.
- The analysis suggests that customer demographics, occupation, and location can help businesses understand purchasing patterns.


## Conclusion
This project demonstrates how Python libraries can be used to clean, analyze, and visualize retail sales data. By comparing customer segments across multiple dimensions, the analysis helps identify potential high-value customer groups and product categories.

## Project Type
Exploratory Data Analysis (EDA) | Retail Analytics | Customer Segmentation | Data Visualization
