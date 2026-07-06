# Model Explanation

## Project Type
This project focuses on data cleaning, feature engineering, and exploratory data analysis (EDA). No machine learning model was developed.

## Workflow

### 1. Data Loading
- Loaded the Online Retail dataset using the Pandas library.
- Inspected the dataset using `head()`, `info()`, `shape`, and `describe()`.

### 2. Data Cleaning
- Checked for missing values using `isnull().sum()`.
- Removed or imputed missing values where appropriate.
- Verified data types and corrected them if necessary.
- Removed duplicate records (if present).

### 3. Feature Engineering
Created new features to enhance analysis:
- **TotalOrderValue** = Quantity × UnitPrice
- **Month** extracted from InvoiceDate
- **Weekday** extracted from InvoiceDate

### 4. Exploratory Data Analysis (EDA)
Performed visual and statistical analysis to understand:
- Sales trends over time
- Distribution of Quantity and UnitPrice
- Top customers by revenue
- Sales by country
- Correlation between numerical variables
- Outlier detection using boxplots

### 5. Data Export
Exported the cleaned and analysis-ready dataset as `cleaned_online_retail.csv`.

## Outcome
The final dataset is clean, enriched with derived features, and ready for business analysis, dashboard creation, or future machine learning tasks.
