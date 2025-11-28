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

{Data Formating}

(![data formart](https://github.com/user-attachments/assets/7690f5a4-70c7-48fa-a022-cb1f639a1249)

{performing Aggregates}

(![Aggregate 1](<img width="634" height="365" alt="Picture4" src="https://github.com/user-attachments/assets/44876bd5-fe79-4662-a2fb-3d33afa8e92c" />

{querying aggregates}

(
<img width="641" height="441" alt="Picture5" src="https://github.com/user-attachments/assets/f5048726-f96f-42dc-833c-ce595b26dba8" />

{querying kpi max and join}

(
<img width="677" height="439" alt="Picture6" src="https://github.com/user-attachments/assets/6cc88ab0-87b2-46fc-81fa-248c9bfbfe55" />

## Next I exported analytical results as CSV for dashboard use.

# Data Visualization
I used Power Bi for data visualization.
After creating the measures and going through the data to ensure that all was fine. I proceeded to the report tab of Power BI to visualize the data

[Customer Demographics]

(<img width="671" height="411" alt="dasgboard1" src="https://github.com/user-attachments/assets/68958372-7a91-4933-ae73-c6967c812149" />

[Customer Segmentation Analysis]

(<img width="676" height="418" alt="dasgboard 2" src="https://github.com/user-attachments/assets/9e67f57a-5b66-4fd0-86c1-6c71127a3bc4" />

[Socioeconomic Analysis]

(<img width="675" height="379" alt="dasgboard 3" src="https://github.com/user-attachments/assets/2f901a4b-44c0-48dd-a373-1aac44516d8a" />

# KEY FINDINGS AND INSIGHTS
• Average customer age: 43.6 years; Work experience: 2.6 years; Family size: 2.75
• 61.5% of customers had low spending scores; 14.7% were high spenders
• Segment A had the most customers (32%), followed by Segment D (29%)

High-Value Segments: Segment C and B contain the highest concentration of customers with high spending scores, graduated professionals like Executives and Lawyers with higher work experience. Married individuals dominate high-value segments, suggesting stability and spending capacity. These groups represent strong purchasing power and brand engagement potential.

Demographic Trends: Segment A skews younger (30-50), while Segment C includes older professionals (60+). Gender is evenly spread across segments, though Segment A has a slight male majority. Education & Profession: Segments D and A have the highest graduate professionals but with the lowest percentage share of high spenders, 11% and 14% respectively. Professionally active roles (Executive and Lawyer) correlate with higher spending(income), higher family sizes and brand loyalty.

Spending Behavior: High spending score is most prevalent in Segments C and B whilst Segment D shows low spending despite varied professions, indicating lower engagement or budget constraints.

# STRATEGIC RECOMMENDATIONS
The Automobile company should:
1. Target Segments C & B for premium offerings, loyalty programs, and personalized marketing.
2. Upskill Segment A with educational content and mid-tier product bundles to boost spending.
3. Re-engage Segment D through budget-friendly campaigns and value-based messaging and develop loyalty programs for this segment.
4. Personalize marketing by profession and education level.
5. Collect income data for improved predictive insights.
