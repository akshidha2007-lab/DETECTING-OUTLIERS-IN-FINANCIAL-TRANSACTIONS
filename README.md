# 💳 Detecting Outliers in Financial Transactions

### 🐍 Python | 📊 Data Cleaning | 🔍 Outlier Detection

## 📌 Project Overview
This project focuses on cleaning financial transaction data and identifying unusual transaction amounts using Python.

The project applies 17 data cleaning steps to improve data quality, handle invalid records, and detect potential outliers using the Interquartile Range (IQR) method.

## 🎯 Objectives
- 🧹 Clean and preprocess financial transaction data.
- 🔄 Remove duplicate records.
- 📅 Standardize date and time formats.
- 📝 Handle missing and invalid values.
- 🔢 Convert transaction amounts into numeric formats.
- 🔍 Identify unusual transaction patterns.
- ✅ Validate data accuracy and consistency.

## 🛠️ Tools & Technologies
- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📓 Jupyter Notebook
- 📗 Microsoft Excel

## 🧹 Data Cleaning Process
A total of 17 data cleaning steps were performed:

1. Removal of empty rows
2. Removal of duplicate records
3. Removal of extra spaces
4. Text case standardization
5. Spelling correction
6. Date format standardization
7. Time format standardization
8. Splitting columns
9. Handling missing values
10. Data type conversion
11. Identification of invalid values
12. Removal of unnecessary columns
13. Removal of unwanted special characters
14. Category standardization
15. Resetting the index
16. Outlier detection using IQR
17. Data validation

## 📊 Outlier Detection
The Interquartile Range (IQR) method was used to identify unusually high or low transaction amounts.

Potential outliers were separated for further investigation instead of being automatically deleted.

## 📈 Project Results

| Metric | Result |
|---|---:|
| Original Records | 3,980 |
| Cleaned Records | 3,968 |
| Duplicate Records Removed | 12 |
| Potential Outliers Identified | 258 |
| Validation Checks Passed | 16/16 |

## 📂 Project Files
- 📓 Python Jupyter Notebook – Data cleaning and outlier detection code.
- 📁 Uncleaned Dataset – Original financial transaction data.
- 📊 Cleaned Dataset – Processed financial transaction data.
- 📄 Data Cleaning Documentation – Details of 17 cleaning steps.

## 💡 Key Learning Outcomes
- Practical experience with Python and Pandas.
- Understanding real-world data cleaning techniques.
- Working with missing and invalid values.
- Applying the IQR method for outlier detection.
- Improving data quality through validation.

## 📝 Conclusion
This project demonstrates how Python can be used to clean financial transaction data and identify potential outliers. It helps improve data reliability and prepares the dataset for further financial analysis and decision-making.

⚠️ **Note:** Identified outliers are potential unusual transactions and are not confirmed fraudulent activities.

---

⭐ *This project is part of my learning journey in Python and Data Analytics.*
