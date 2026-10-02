🧹 Excel Data Cleaning & Transformation – Product Dataset
📖 Project Overview
This project demonstrates practical data cleaning and preparation techniques using Microsoft Excel.
The dataset contains product information with common real-world issues such as missing values, inconsistent formatting, duplicate records, and unstructured text fields.
The goal of this assignment is to apply Excel’s cleaning tools to improve data quality, usability, and readability for analysis.

📁 Dataset Description
The dataset includes the following attributes:

Attribute	Description
Product ID	Unique identifier combining manufacturing date and country code
Manufacturing Date	Date of product manufacturing
Country Code	Country of origin
Product Name	Name of the product
Brand Name	Manufacturer or brand
Product Brand	Combined field of Brand Name + Product Name
Price ($)	Product price in USD
Quantity	Units available
Category	Product category (Electronics, Fashion, Kitchen, etc.)


🛠️ Tasks Performed
1. Handling Missing Values
Checked for missing values in the Price column.

Formula used: IF(ISBLANK(E2),AVERAGE(E2:E39),E2)

Imputed missing Category values with "Unknown" using:

IF(ISBLANK(G2),"Unknown",G2)

2. Correcting Inconsistent Data
Identified inconsistent text formats in Product Name (e.g., Smartphone, Headphone, Laptop).

Detected typo errors in Category (e.g., “Electronics” misspelling).

Standardized text formats using Find & Replace.

3. Removing Duplicates
Checked for duplicate rows across the dataset.

Found and removed 3 duplicate records.

4. Splitting and Merging Data
Split Product ID into Manufacturing Date and Country Code.

Merged Brand Name and Product Name into a new column Product Brand.

5. Number Formatting
Formatted Price column into Currency format.

Converted Manufacturing Date into DD-MM-YYYY format.

6. Conditional Formatting
Applied data bars and color scales in the Price column.

Created a custom rule to highlight Category = Electronics.

🎯 Key Learning Outcomes
Gained hands-on experience in data preprocessing.

Learned techniques for handling missing values and imputations.

Improved dataset consistency through standardization.

Applied conditional formatting for better visualization.

Strengthened skills in Excel functions and transformations.

🧩 Tools Used
Microsoft Excel

Functions: IF, ISBLANK, AVERAGE.

Features: Find & Replace, Remove Duplicates, Conditional Formatting, Text Functions.
