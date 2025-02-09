# Retail Sales and Customer Behavior Analysis

This Jupyter Notebook performs an exploratory data analysis (EDA) on a retail dataset to understand customer behavior, sales trends, and factors influencing customer churn.

## Dataset

The analysis uses a retail dataset containing information about customer demographics, transactions, and store locations. The dataset can be downloaded from Kaggle: [link to dataset].

## Analysis Steps

1. **Data Preparation:**
   - Load the dataset using Pandas.
   - Handle missing or incorrect values.

2. **Exploratory Data Analysis and Visualization:**
   - **Customer Distribution:** Analyze age and gender distribution using histograms and countplots.
   - **Transactional Data:** Identify top product categories by sales and average purchase value by payment method using barplots.
   - **Customer Behavior:** Explore purchase frequency distribution and the impact of loyalty programs on total sales using countplots and boxplots.
   - **Sales Trends:** Analyze monthly sales trends using line plots.
   - **Customer Churn Analysis:** Investigate factors influencing customer churn, such as average purchase value and purchase frequency, using boxplots.
   - **Correlation:** Compute and visualize the correlation matrix to identify relationships between variables using a heatmap.

3. **Key Insights:**
   - Identify customer segments with the highest average purchase value based on age, gender, and income bracket.
   - Analyze the impact of promotions on sales and customer behavior.
   - Determine store locations with the highest sales and contributing factors.

## Libraries Used

- Pandas
- Matplotlib
- Seaborn
- Opendatasets

## Usage

1. Download the dataset from the provided link.
2. Install the necessary libraries.
3. Run the Jupyter Notebook cells sequentially to perform the analysis.

## Results

The notebook provides visualizations and insights into customer behavior, sales trends, and factors influencing customer churn. These findings can be used to make informed business decisions related to marketing, inventory management, and customer retention.
