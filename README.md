# Customer-Segmentation
Thrive Data Internship Project Gp10
# Overview:
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4, and P5). After intensive market research, they’ve deduced that the behavior of the new market of 2,627 new customers is similar to their existing market. The dataset of the identified 2,627 new potential customers of the Automobile Company includes customer records with demographic, educational, professional, and behavioral attributes. Key fields include Age, Gender, Marital Status, Education, Profession, Work Experience, Spending Score, and Family Size.
# About the Project:
The objective of this project was to analyze customer demographic and behavioral data to identify key patterns, perform customer segmentation using RFM metrics and identify high-value customer groups. 
# Tools Used:
Excel and Power Query was used for data cleaning, MySQl was used for exploration and Power BI for analysis and visualization. 
# About the Dataset:
This dataset is about customers of an automobile company and their purchase parttern. The data contains 10 columns and 2,627 rows. The columns which are CustomerID,	Gender, Marital Status,	Age,	Graduated,	Profession,	Work Experience,	Spending Score,	Family Size and	Segmentation.
The data was gotten from kaggle
{Download here}(https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation)

# Data Cleaning
The data set named 'Train' was imported in a comma seperated value (csv) format into Excel and Power Query, after that the data cleaning process commenced. Kindly follow through to see the steps I took to clean the data.
The first thing I had to do was to standardize the date format.
Replaced null values in the 'Work Experience' column with avaerage of 2.6, 
Replaced nul values in the Family Size column with 1 to represent the customer only, 
Updated null values in Profession column with NA.
Updated all Columns with appropriate and uniform data type.

# Data Exploration
MySQl was used for data exploration. The cleaned data was imported in a comma seperated value (csv) format into Microsoft SQL server using the import and export wizard. Perform aggregations, joins and KPI calculations.

{Data Formating}(![data formart](https://github.com/user-attachments/assets/7690f5a4-70c7-48fa-a022-cb1f639a1249)

{performing Aggregates}(![Aggregate 1](https://github.com/user-attachments/assets/790c9783-9c2c-41ca-8da3-7e854dd23f19)

{querying aggregates}(![aggregat 2 avg - min](https://github.com/user-attachments/assets/d4d11f1c-d472-42a5-a86c-8783d44df103)

{querying kpi max and join}(![aggregate 2 max n joins](https://github.com/user-attachments/assets/314d2417-63a1-4c35-921a-3b4376ab8f67)


Export analytical results as CSV for dashboard use.


