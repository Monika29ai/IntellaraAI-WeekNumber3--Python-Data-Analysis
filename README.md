# IntellaraAI-WeekNumber3-Python-Data-Analysis
Analyzing data using pandas
# Online Retail Data Cleaning & Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on cleaning and analyzing an Online Retail dataset to extract meaningful business insights. The workflow includes data preprocessing, feature engineering, exploratory data analysis (EDA), and visualization to prepare the dataset for further analysis and business decision-making.

## Objectives

* Clean and preprocess the dataset
* Handle missing values and duplicates
* Engineer new features
* Perform exploratory data analysis
* Visualize key business insights
* Export the cleaned dataset

## Dataset

The dataset contains online retail transactions with the following columns:

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Preprocessing

* Inspected dataset structure and data types
* Handled missing values
* Converted `InvoiceDate` to datetime format
* Created new features:

  * TotalOrderValue
  * Month
  * Weekday

## Exploratory Data Analysis

Performed analysis to:

* Understand data distributions
* Detect outliers
* Analyze sales trends
* Identify top customers
* Compare sales across countries

## Visualizations

* Sales Over Time
* Top Customers by Revenue
* Top Countries by Sales
* Quantity and Unit Price Distribution
* Outlier Boxplots

## Key Insights

* High-value customers contribute significantly to overall revenue.
* Sales vary across countries and time periods.
* Negative quantities indicate returned products.
* Feature engineering improved business analysis and reporting.

## Output

The cleaned dataset is exported as:

`cleaned_online_retail.csv`

## How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

or

```bash
python eda.py
```


