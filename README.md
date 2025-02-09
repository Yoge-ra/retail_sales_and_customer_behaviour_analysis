# Retail Sales and Customer Behavior Analysis

This Jupyter Notebook performs an exploratory data analysis (EDA) on a retail dataset to understand customer behavior, sales trends, and factors influencing customer churn.

## Dataset

The analysis uses a retail dataset containing information about customer demographics, transactions, and store locations. The dataset can be downloaded from Kaggle: [https://www.kaggle.com/datasets/utkalk/large-retail-data-set-for-eda].

## About Dataset
### Data Set Description
This dataset simulates a retail environment with a million rows and 100+ columns, covering customer information, transactional data, product details, promotional information, and customer behavior metrics. It includes data for predicting total sales (regression) and customer churn (classification).

### Detailed Column Descriptions
#### Customer Information:

   -`customer_id:` Unique identifier for each customer.
   -`age:` Age of the customer.
   -`gender:` Gender of the customer (e.g., Male, Female, Other).
   -`income_bracket:` Income bracket of the customer (e.g., Low, Medium, High).
   -`loyalty_program:` Whether the customer is part of a loyalty program (Yes/No).
   -`membership_years:` Number of years the customer has been a member.
   -`churned:` Whether the customer has churned (Yes/No) - Target for classification.
   -`marital_status:` Marital status of the customer.
   -`number_of_children:` Number of children the customer has.
   -`education_level:` Education level of the customer (e.g., High School, Bachelor's, Master's).
   -`occupation:` Occupation of the customer.

#### Transactional Data:

   -`transaction_id:` Unique identifier for each transaction.
`transaction_date:` Date of the transaction.
`product_id:` Unique identifier for each product.
`product_category:` Category of the product (e.g., Electronics, Clothing, Groceries).
`quantity:` Quantity of the product purchased.
`unit_price:` Price per unit of the product.
`discount_applied:`` Discount applied on the transaction.
`payment_method:` Payment method used (e.g., Credit Card, Debit Card, Cash).
`store_location:` Location of the store where the purchase was made and many ....


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
