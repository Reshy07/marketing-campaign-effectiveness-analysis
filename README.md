# Superstore Data Analysis
## Overview
This Jupyter Notebook performs an initial exploratory data analysis (EDA) on the "superstore_data.csv" dataset. The dataset contains information about customers, including demographic details, purchasing behavior, and responses to marketing campaigns.

## Dataset Information
    - Shape: 2240 rows, 22 columns
    -Columns: The dataset includes features such as:
         -Customer ID (Id)
         -Demographic information (Year_Birth, Education, Marital_Status, Income)
         -Household information (Kidhome, Teenhome)
         -Customer enrollment date (Dt_Customer)
         -Purchasing behavior (Recency, MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds)
         -Purchase channels (NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases)
         -Web activity (NumWebVisitsMonth)
         -Campaign response (Response)
         -Customer complaints (Complain)

## Data Exploration
    The notebook includes:
    -Loading the dataset and displaying the first few rows.
    -Checking dataset information (data types, non-null counts).
    -Generating summary statistics for numerical columns.
    -Identifying missing values (notably 24 missing values in the Income column).
    -Visualizing the distribution of the Income column using a histogram.
    -Handling missing values in the Income column by imputing with the median value.

## Key Steps
    1.Data Loading: The dataset is loaded using pandas.
    2.Initial Inspection: Basic information about the dataset is printed, including shape, first rows, and data types.
    3.Summary Statistics: Descriptive statistics are generated for numerical columns.
    4.Missing Values: Missing values are identified and handled (median imputation for Income).
    5.Visualization: A histogram is plotted to understand the distribution of Income.

## Requirements
    Python 3.x
    Libraries: pandas, numpy, matplotlib, seaborn

## Usage
    -Ensure the dataset "superstore_data.csv" is in the correct path.
    -Run the cells in sequence to perform the EDA.
    -The notebook can be extended for further analysis, such as feature engineering, modeling, or additional visualizations.

## Notes
    -The Income column was right-skewed, so median imputation was chosen for handling missing values.
    -Further analysis could include correlation studies, segmentation, or predictive modeling based on customer behavior.
