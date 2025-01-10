# Exploratory Data Analysis (EDA) on Customer Segmentation Dataset

## Problem Statement
This project aims to perform Exploratory Data Analysis (EDA) on the customer segmentation dataset to uncover insights into customer demographics, purchasing behaviors, and transaction patterns. These insights will guide the company in identifying potential segments for targeted marketing.

## Objective
The objective of this project is to analyze customer data to identify meaningful patterns and trends that can assist in customer segmentation for targeted marketing. By understanding customer behaviors and characteristics, the company will be able to create more effective marketing strategies.

## EDA Steps

### 1. Data Cleaning and Preprocessing:
- **Handle Missing Values**: Identify and manage missing or null entries in key fields.
- **Data Types Verification**: Ensured that data types are consistent for both numerical and categorical features through LabelEncoder.
- **Duplicate Removal**: Detect and remove any redundant records.

### 2. Univariate Analysis:
#### Demographics Overview:
- Visualize the distribution of age, income, and gender using histograms and boxplots.
- Identify outliers and check for skewness in numerical data.

#### Spending Patterns:
- Examine spending scores and purchase frequencies to determine the overall customer spending behavior.

### 3. Bivariate Analysis:
#### Correlation Analysis:
- Analyze relationships between age, income, and spending patterns using heatmaps and correlation matrices.

#### Gender vs. Spending:
- Compare spending behavior across gender using bar charts and violin plots.

#### Income vs. Purchase Frequency:
- Identify trends between customer income levels and their frequency of purchases.

### 4. Categorical Analysis:
#### Customer Segments by Category:
- Group and visualize customers based on marital status or age ranges.
- Identify patterns in high-spending categories.

### 5. Visualization:
- Use scatter plots to detect clusters visually (e.g., income vs. spending score).
- Heatmaps for visualizing correlations between multiple numeric features.
- Pie charts to understand the proportion of different customer segments.

## Tools and Libraries Used:
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

## Dataset
The dataset used for this analysis includes customer demographics, transaction data, and purchase behavior. The columns in the dataset include customer age, gender, income, spending score, and frequency of purchases.




