# ELEVETLABS_Task-1_Sales-Data #

**Task 1: Data Cleaning and Preprocessing**

🧹 Data Cleaning and Preprocessing Summary 
✅ Task Overview 

1. I worked on a raw auto sales dataset which required cleaning and preprocessing using both Excel and Python (Jupyter Notebook). The steps I followed are outlined below:

- Initial Review (Excel):

- Opened the raw dataset in Excel.

- Cleaned up values by:

- Converting text to lowercase

- Removing special characters

- Standardizing columns and values

- Saved the cleaned version for use in Python.

2. Python (Jupyter Notebook):

- Loaded the cleaned Excel file using pandas.

- Used libraries like pandas and numpy to:

- Explore data using .head(), .info(), .describe()

- Standardize date formats

- Remove duplicates

- Validate column types and formats

3. Repository & Submission:

- Created a GitHub repository to host:

- Cleaned dataset (CSV & Excel)

- Python cleaning script


💡 **Key Data Cleaning Concepts (Interview Q&A)**

1. What are missing values and how do you handle them?
   Missing values are blanks or NaN in datasets. They can be handled by:

- Removing rows (dropna())

- Filling with appropriate values (fillna()), like mean, median, or mode.

2. How do you treat duplicate records?
   Duplicates are removed using drop_duplicates() to ensure accuracy and avoid bias in analysis.

3. Difference between dropna() and fillna() in Pandas?

- dropna() removes rows or columns with null values.

- fillna() replaces missing values with a specified value (like mean, median, etc.).

4. What is outlier treatment and why is it important?
   Outlier treatment involves identifying and handling extreme values that can skew analysis. Techniques include capping, transformation, or removal.

5. Explain the process of standardizing data.
   Standardization means bringing data to a common format — e.g., consistent text casing, date formats, units, and column naming conventions.

6. How do you handle inconsistent data formats (e.g., date/time)?
   Use pd.to_datetime() with errors='coerce' and dayfirst=True to parse and convert all dates into a standard format.

7. What are common data cleaning challenges?

- Inconsistent formatting

- Missing or incorrect values

- Duplicate entries

- Mixed data types

- Unstructured or poorly labeled columns

8. How can you check data quality?
- Use .info(), .isnull().sum(), .duplicated().sum(), data type checks, and domain knowledge to validate and ensure clean, high-quality data.
