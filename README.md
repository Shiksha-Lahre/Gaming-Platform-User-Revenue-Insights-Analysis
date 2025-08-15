# Gaming-Platform-User-Revenue-Insights-Analysis
This project provides a comprehensive analysis and dashboard for the gaming user dataset. It aims to uncover actionable insights through exploratory data analysis (EDA) and intuitive visualizations to drive data-informed decisions.

**File description**

- Data.csv :	The original raw dataset used for analysis.

- filtered_data.xlsx :	Cleaned and preprocessed version of the data, ready for analysis.

- Activity.ipynb : Jupyter Notebook containing step-by-step data cleaning, EDA, and visualizations.

- Dashboard.pbix :	Power BI dashboard that brings the key insights to life.

- Insight report.pdf :	A visual report summarizing key findings and actionable recommendations.

**Project Flow**

**1. Importing Raw Data:** The dataset was loaded into the analysis environment using Python (pandas). Initial inspection was done to understand data structure, column types, and missing values.

**2. Data Validation:** Checked for logical inconsistencies (e.g., Last Login date earlier than Signup date). Removed 215 invalid rows to ensure data integrity, resulting in a clean dataset of 9,785 records.

**3. Data Transformation:** Standardized date formats for time-series analysis. Corrected inconsistent text labels (e.g., subscription types, device names). Filtered irrelevant columns for performance optimization.

**4. Exporting Clean Data:** Saved the cleaned dataset as filtered_data.xlsx for use in both the Jupyter Notebook and Power BI.

**5. Exploratory Data Analysis (EDA)** - **Descriptive Statistics:** Computed KPIs such as DAU (Daily Active Users), WAU (Weekly Active Users), and MAU (Monthly Active Users). Calculated total revenue, device-wise revenue, subscription-wise performance, and game mode preferences.

**6. Trend & Pattern Analysis:** Identified peak engagement days (e.g., Wednesdays and Thursdays) and seasonal dips. Studied revenue patterns over time to align feature launches with high-traffic days.

**7. User Segmentation:** Classified users into free, silver, gold, and platinum categories. Analyzed device preferences (Console, Mobile, PC) and their revenue contributions.

**8. Visualization:** Created bar charts, line graphs, and pie charts to clearly illustrate user activity, revenue trends, and churn patterns in the Jupyter Notebook.

**9. Dashboard Creation (Power BI):** Imported the cleaned filtered_data.xlsx into Power BI Desktop. Built an interactive dashboard with:
- Time-series visualizations for DAU/WAU/MAU.
    
- Revenue breakdowns by device, subscription type, and game mode.
   
- Geographical maps showing country-wise user engagement and churn rates.
   
- User segmentation visuals for high-value users and churn-risk profiles.
   
- Added slicers and filters to allow stakeholders to explore the data by date range, user type, or device category.
   
**10. Insight Report:** Compiled a professional PDF report summarizing:

  - Key Findings: Peak usage times, revenue-driving segments, churn indicators.
  
  - Cohort Analysis: Weekly retention patterns, anomalies, and deviations from typical decline curves.
  
  - Revenue Insights: Device and subscription contributions, multiplayer dominance.

**11. Recommendations:**

- Weekend-only flash discounts to boost engagement.

- Multiplayer enhancements (seasonal content, battle passes, avatars).

- Console-specific rewards and challenges.

- Structured the report for easy consumption by stakeholders, highlighting actionable next steps.

**Tools & Technologies**
1. Python (pandas, matplotlib, seaborn, numpy)
2. Jupyter Notebook
3. Power BI Desktop
4. Data visualization and reporting
5. Excel

**Project Summary**

Conducted an in-depth analysis of a gaming platform’s user activity, revenue trends, and retention patterns using cleaned and validated data (9,785 rows after removing inconsistencies). Analyzed DAU/WAU/MAU metrics, peak usage days, and device-based revenue contribution, revealing that consoles generated the highest revenue and Wednesdays/Thursdays drove maximum engagement. Segmented revenue by subscription tiers and game modes, highlighting multiplayer games as the top revenue source. Identified early churn signals through signup–last login gaps and low session duration patterns, and profiled top 10% high-value users. Performed cohort analysis to study retention trends across signup weeks. Recommended strategies such as weekend flash discounts, multiplayer feature enhancements, and console-exclusive content to boost engagement and revenue.

