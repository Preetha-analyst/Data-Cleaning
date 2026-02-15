# Data Cleaning and Preprocessing - Mall Customer Dataset

##Objective
To clean and prepare a raw dataset by handling missing values, duplicates, 
standardizing column names, and checking data types.

##Dataset Used
Mall Customers Dataset

Columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

##Tools Used
Python
Pandas

##Steps Performed

1. Loaded dataset using pd.read_csv()
2. Checked dataset shape using df.shape
3. Examined dataset info using df.info()
4. Generated statistical summary using df.describe()
5. Checked missing values using df.isnull().sum()
6. Checked duplicate records using df.duplicated().sum()
7. Renamed column names:
   - Converted to lowercase
   - Replaced spaces with underscore
   - Removed brackets and special characters
8. Checked unique values in gender column
9. Verified data types
10. Checked for outliers in age column
11. Removed unrealistic age values (>100)
12. Saved cleaned dataset as cleaned_mall_customers.csv

##Result
The dataset was cleaned and structured properly.
No missing values or duplicate records found.
Column names standardized.
Dataset ready for further analysis or modelling.
