E-Commerce Data Cleaning, Analysis & Visualization – Summary
For this assignment, I worked with an E-Commerce dataset using Power Query and Microsoft Excel.
1. Data Cleaning and Transformation
I imported all tables into Power Query and performed data cleaning operations.
Customer_Dim
Removed extra spaces using Trim and Clean functions. 
Standardized text formatting. 
Handled missing values in the Loyalty_Level column. 
Checked and removed duplicate records. 
Created a merged column for better organization. 
Product_Dim
Identified inconsistent Product_ID values such as P-3 and P-16 and standardized them to the PROD format. 
Cleaned Product_Name, Category, Sub_Category, and Brand columns. 
Replaced missing values in the Cost column using the average cost value. 
Replaced missing values in the Stock column using the average stock value. 
Created merged columns such as Product_Brand and Product_Type. 
Checked and removed duplicate records. 
Store_Dim
Verified all records and data types. 
Cleaned text fields using Trim and formatting transformations. 
Checked for duplicate records and missing values. 
Sales_Fact
Verified data consistency and formatting. 
Replaced missing values in Quantity, Unit_Price, Discount, and Total_Amount using average values. 
Validated data types and checked for duplicates. 

2. Combining Tables
I combined the cleaned tables using VLOOKUP.
Using Customer_ID, Product_ID, and Store_ID, I retrieved:
Customer Name 
Product Name 
Store Name 
This helped create a single analysis table for reporting and visualization.

3. Excel Formulas Used
I applied the following Excel formulas:
SUM 
AVERAGE 
COUNTIF 
IF 
TEXT 
These formulas were used to calculate sales totals, averages, order counts, sales categorization, and date formatting.

4. Descriptive Statistics
I calculated the following statistical measures:
Mean 
Median 
Mode (No repeating value found in some cases) 
Standard Deviation 
Minimum Value 
Maximum Value 
These statistics helped understand the distribution and variability of sales data.

5. Pivot Tables
I created Pivot Tables to summarize data from different perspectives:
Category-wise Sales Analysis 
Store-wise Sales Analysis 
Customer-wise Sales Analysis 
These Pivot Tables provided meaningful insights into sales performance.

6. Data Visualization
I created the following charts:
Column Chart – Sales by Category 
Pie Chart – Store Contribution to Total Sales 
Line Chart – Sales Trend Over Time 
These visualizations helped present the analysis in a clear and understandable manner.

7. Dashboard
Finally, I created an E-Commerce Sales Dashboard that combines charts and summarized information into a single view.
The dashboard provides:
Sales performance overview 
Category-wise sales comparison 
Store-wise contribution analysis 
Sales trend analysis 

Conclusion
This project helped me understand the complete data analysis process, including data cleaning, transformation, table integration, formula usage, statistical analysis, Pivot Tables, data visualization, and dashboard creation using Excel and Power Query. The final dashboard provides meaningful business insights and supports data-driven decision-making.

PFA the Word file containing the screenshots that show the formulas used and the steps performed for your reference.
