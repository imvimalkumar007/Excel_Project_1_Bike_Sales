
# Bike Sales Data Analysis Project

## Project Overview
This project analyzes a dataset of bike sales, sourced from Kaggle, to identify key trends and insights into customer behavior. The goal was to clean the raw data, create meaningful visualizations, and build a comprehensive dashboard to summarize the findings.

## Dataset Details
- **Source:** Kaggle
- **Content:** The dataset includes customer demographic information, income levels, commute distances, marital status, and bike purchase decisions.

## Data Cleaning Steps
1. **Trimming and Formatting:**
   - Removed leading and trailing spaces from data fields.
   - Standardized text formatting for consistency.
2. **Duplicates:**
   - Identified and removed duplicate records to ensure data integrity.
3. **Find and Replace:**
   - Replaced abbreviated terms such as “M/F” with “Male/Female” and “M/S” with “Married/Single.”
4. **Concatenation:**
   - Combined related fields for improved clarity.
5. **Filters:**
   - Applied filters to remove unnecessary or irrelevant data fields.
6. **Age Brackets:**
   - Added a calculated column to categorize customers into age groups (Adolescent: 0-30, Middle-aged: 31-54, Old: 55+).

## Data Analysis Process
- **Working Dataset:**
  - Created a refined dataset with cleaned and formatted data, adding calculated columns for deeper analysis.
- **Pivot Tables:**
  - Generated four pivot tables to extract insights from the data:
    1. **Average Income by Gender and Purchase Decision:**
       - Compared income levels of customers based on gender and whether they purchased a bike.
    2. **Customer Age Ranges by Purchase Decision:**
       - Analyzed age brackets to identify trends in bike purchases.
    3. **Commute Distance by Purchase Decision:**
       - Explored how commute distances influenced bike purchases.
    4. **Customer Distribution by Region:**
       - Investigated regional differences in bike purchases.

## Visualizations and Dashboard
- **Dashboard Overview:**
  - Built a user-friendly dashboard summarizing key insights.
  - Visualizations include:
    1. **Average Income Per Purchase Decision by Gender**
    2. **Customer Age Ranges**
    3. **Commute Distance and Purchase Trends**
    4. **Regional Purchase Trends**
- **Tools Used:**
  - Microsoft Excel for data cleaning, pivot tables, and dashboard creation.

## Key Insights
1. **Income Levels:**
   - Male customers tend to have higher average incomes, irrespective of bike purchase decisions.
2. **Age Trends:**
   - Middle-aged customers (31-54) represent the largest segment of bike purchasers.
   - Adolescents (0-30) and older customers (55+) are less likely to purchase bikes.
3. **Commute Distance:**
   - Customers commuting shorter distances (0-1 miles) are more likely to purchase bikes.
4. **Regional Trends:**
   - Purchases vary significantly across regions, with Europe showing the highest bike purchase rates.

## Conclusion
This project demonstrates how effective data cleaning and analysis can reveal actionable insights from raw data. The dashboard provides a clear summary of trends and can be used by stakeholders to make informed business decisions regarding bike sales and marketing strategies.

## Future Work
1. **Advanced Analysis:**
   - Implementing machine learning models for predictive analysis.
2. **Integration:**
   - Combining this data with sales data from other product categories.
3. **Automation:**
   - Automating data cleaning and reporting processes.

---

### Files Included
1. **Raw Data:** Original dataset from Kaggle.
2. **Cleaned Data:** Refined dataset used for analysis.
3. **Dashboard:** Visual summary of the findings.
4. **Pivot Tables:** Supporting tables for the dashboard.


