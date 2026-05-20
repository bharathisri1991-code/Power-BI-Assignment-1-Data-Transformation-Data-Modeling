📊 Power BI Assignment 1 – Data Transformation & Data Modeling

📁 Project Overview

This project demonstrates the complete workflow of data transformation, cleaning, aggregation, and data modeling in Power BI using Power Query Editor and Model View.

The assignment includes:

Data import and preparation
Data cleaning and transformation
Conditional logic and calculated columns
Merging and aggregating datasets
Data modeling and relationship managementData Import & Transformation:
Imported List of Orders.csv, Order Details.csv, and Sales Target.csv into Power BI    using the Get Data option. Opened all datasets in Power Query Editor through the   Transform Data feature for further data cleaning and transformation.

Row Limiting & Data Types:
  Restricted the List of Orders dataset to the first 500 rows using the Keep Top Rows option in Power Query Editor. Converted the Order Date column to Date data type and changed the Amount and Target columns to Fixed Decimal Number format for accurate analysis and calculations.

Text Formatting:
Formatted the Customer Name column using the Capitalize Each Word option in Power Query Editor to maintain consistent capitalization and improve data quality.

Column Creation:
 Merged the City and State columns to create a Location field in the format “City, State”. Added a custom column named Profit Margin using the formula Profit divided by Amount and formatted the result as a percentage for profitability analysis.

 Conditional Column:
Added a conditional column named Profit Status using conditional logic in Power Query Editor. Classified records as Loss, Break-Even, or Profit based on profit values to support profitability analysis.
 
 Merging Data (Joins):
Merged the List of Orders and Order Details tables using the Order ID field with a Left Outer Join in Power Query Editor. Expanded the required columns and renamed the merged table as Orders Data for unified analysis.

Handling Missing Data & Duplicate Data:
Checked all tables for missing values, nulls, and errors using column quality indicators in Power Query Editor. No missing or erroneous values were found in the final Orders Data table. Duplicate handling was performed carefully using business logic, retaining repeated Order IDs where multiple products belonged to the same order, and removing only completely identical duplicate records.
 
 Sorting and Filtering Data:
 Sorted the Orders Data table by Order Date in descending order to display the most recent orders first. Applied filters to analyze orders from a specific state, Tamil Nadu, enabling focused regional analysis.
 
Grouping and Aggregating Data: 
 Duplicated the Order Details and Sales Target tables to perform aggregation operations. Calculated the count of Order IDs, average profit by category, total amount by sub-category, and total sales target by month using the Group By feature in Power Query Editor for summarized business analysis. Duplicated the Sales Target table and aggregated the Target values by Month of Order Date using the Group By transformation in Power Query Editor to generate monthly sales target summaries.

Data Modeling:
Established data model relationships between List of Orders and Order Details using Order ID, and between Order Details and Sales Target using Category. Verified and managed relationships using the Manage Relationships feature to ensure all relationships were active and correctly configured for accurate reporting and analysis.
 
Data Modeling Logic
Relationships were established between the tables to enable accurate reporting and filtering across datasets. The List of Orders table was connected with the Order Details table using Order ID, while the Order Details table was connected with the Sales Target table using Category.
The relationships were configured and verified using the Manage Relationships feature in Power BI to ensure they were active and correctly defined. Proper cardinality and cross-filter directions were selected based on business logic to maintain data integrity and support efficient analysis across related tables.
 
