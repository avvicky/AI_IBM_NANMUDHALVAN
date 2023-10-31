# Market Basket Analysis using Apriori Algorithm and Association Rule Mining

This Jupyter notebook contains Python code for performing Market Basket Analysis on sales data using the Apriori algorithm and generating association rules. The analysis includes data cleaning, exploratory data analysis (EDA), and association rule mining. 

## Prerequisites

Before running this notebook, ensure that you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- mpld3

You can install the required Python libraries using pip:


This notebook is memory-intensive and requires at least 20GB of RAM to run successfully due to the size of the dataset and the computational demands of the Apriori algorithm. Make sure your system has enough available memory.

## Steps

1. **Data Hygiene (Step 1):** In this step, the script performs data cleaning tasks, such as dropping rows with missing values, handling negative quantities, filling missing customer IDs, and creating a new column for total sales revenue.

2. **Exploratory Data Analysis (EDA) (Step 2):** This section explores the dataset to identify popular items in each country, total sales by country, and other insights. It also highlights anomalies and unique data patterns.

3. **Market Basket Analysis (Step 3):** This step focuses on market basket analysis using the Apriori algorithm and association rule mining. It involves converting the dataset into a transactional format, creating a one-hot matrix of products, merging the transactional matrix and one-hot matrix, and performing frequent itemset mining and association rule generation.

4. **Visualization:** The notebook includes visualization of association rules using a scatter plot with interactive tooltips.

5. **Results:** The script displays the top association rules by lift, and you can also customize the filtering criteria for association rules based on lift values.

## Running the Notebook

1. Ensure you have the required dependencies installed (as mentioned in the "Prerequisites" section).

2. Download the dataset and save it to an appropriate location.

3. Open the Jupyter Notebook by running the following command in your terminal:

4. Change the path for reading the dataset in read_excel() function.

5. Open this notebook in Jupyter and run each cell sequentially.

6. Follow the code comments and explanations within the notebook for a step-by-step understanding of the analysis.

7. The notebook generates association rules and displays them visually using interactive tooltips.

## Note

This notebook is resource-intensive and requires substantial computational power, especially RAM. Ensure your system can handle the analysis.
