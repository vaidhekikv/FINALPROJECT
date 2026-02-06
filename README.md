# FINALPROJECT
## Project Overview
This project performs Exploratory Data Analysis (EDA) on a synthetically generated customer dataset using Python. The goal is to understand income and spending patterns across different regions through data inspection, cleaning, statistical analysis, and visualization.
The dataset is artificially created to simulate real‑world customer data and is suitable for learning and demonstrating EDA techniques
## Technologies Used

•	Python
•	NumPy – numerical computations and random data generation
•	Pandas – data manipulation and analysis
•	Matplotlib – basic data visualization
•	Seaborn – advanced statistical visualization

## Dataset Description
The dataset contains 1000 rows and 3 columns:
Column Name	Description
Income	Customer annual income (synthetically generated)
Spend	Customer annual spending (synthetically generated)
Region	Geographic region (North, South, East, West)
Note: Income and Spend values are generated using a normal distribution and converted to positive values to avoid negatives

## Dataset Description

The dataset contains 1000 rows and 3 columns:
Column Name	Description
Income	Customer annual income (synthetically generated)
Spend	Customer annual spending (synthetically generated)
Region	Geographic region (North, South, East, West)
Note: Income and Spend values are generated using a normal distribution and converted to positive values to avoid negatives
## Data Generation Process

•	Random seed set for reproducibility
•	Income generated with a mean of 50,000 and standard deviation of 15,000
•	Spend generated with a mean of 20,000 and standard deviation of 8,000
•	Region assigned randomly from four categories

## Data Cleaning & Validation 

The following steps were performed: - Converted negative income and spend values to absolute values - Checked for missing values (none found) - Verified data types - Removed potential inconsistencies

## Exploratory Data Analysis

1️ Initial Data Inspection
•	Displayed first few rows of the dataset
•	Checked dataset shape and column information
2️ Descriptive Statistics
•	Mean, median, standard deviation, minimum, and maximum values for numeric features
3️ Categorical Analysis
•	Frequency count of customers by region

## Visualizations

 Income Distribution
•	Histogram with KDE curve
•	Helps understand income spread and skewness
 Spend Distribution
•	Boxplot visualization
•	Identifies spread and potential outliers
Income vs Spend Relationship
•	Scatter plot colored by region
•	Shows correlation patterns and regional differences

## Key Insights

•	Income and spending values follow approximately normal distributions
•	No missing data present in the dataset
•	Spending generally increases with income
•	Regional distribution of customers is fairly balanced

Conclusion

This project demonstrates a complete EDA workflow, from data generation and cleaning to visualization and insight extraction. It serves as a strong foundation for further analysis, feature engineering, or predictive modeling








