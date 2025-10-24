📊 HR Analytics Dashboard: Employee Attrition Analysis Author: G.V. Shivanjan

Date: October 2025

🎯 Objective The primary goal of this project is to perform an in-depth exploratory data analysis (EDA) on employee attrition data. This analysis aims to uncover the key factors driving employee turnover. The findings are presented in an interactive Power BI dashboard, providing the HR department with actionable insights to make data-driven decisions, improve employee retention, and reduce associated costs.

💾 Dataset Information Dataset: 01_HR_Attrition_Cleaned.csv (The final cleaned dataset used for the dashboard, derived from the initial analysis).

Content: This dataset contains employee records with 26 columns, including key features such as:

Age

Attrition (and Attrition_Flag)

BusinessTravel

Department

DistanceFromHome

JobSatisfaction

JobRole

Salary

OverTime

TotalWorkingYears

Years_At_Company

🚀 Steps Followed

Data Loading & Cleaning: Loaded the raw dataset into a Pandas DataFrame. Checked for and handled missing values, and corrected data types.

Feature Engineering: Created a new binary feature, Attrition_Flag, to represent "Yes" (1) and "No" (0) for easier analysis.

Exploratory Data Analysis (EDA): Performed in-depth analysis in a Jupyter Notebook using Pandas, Matplotlib, and Seaborn. This involved creating various plots (boxplots, countplots, and a correlation heatmap) to analyze distributions and identify key drivers of attrition.

Dashboard Development: Imported the cleaned CSV (01_HR_Attrition_Cleaned.csv) into Power BI. Developed DAX measures for key metrics (like Attrition Rate) and built a two-page interactive dashboard to visualize the findings for non-technical stakeholders.

💡 Key Insights The EDA process revealed several critical factors correlated with employee attrition:

Departments like Sales and R&D show higher attrition compared to HR.

Employees with lower salary ranges have higher attrition.

Employees with 2 years or less at the company tend to leave more frequently.

Low job satisfaction (scores of 1 or 2) strongly correlates with attrition.

Overtime workers leave significantly more often than non-overtime employees.

The correlation heatmap showed that Salary, Total Years at Company, and Job Satisfaction are all negatively correlated with Attrition.

📈 Visualizations The final analysis is presented in a two-page Power BI dashboard, allowing stakeholders to explore the data interactively.

1. Attrition Overview: Provides a high-level snapshot of attrition rates, key metrics, and the top financial and departmental factors.

2. Demographic Analysis: Allows for a deep dive into attrition trends based on demographics like Job Role, Gender, and Marital Status.

🛠️ Tools & Libraries Used

Python

Jupyter Notebook

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For statistical data visualization.

Power BI: For building the interactive dashboard.

🚀 Installation & Usage To explore this project:

View the Analysis: The 01_EDA_and_Data_Cleaning.ipynb notebook contains all Python code used for the EDA and data preparation.

Interact with the Dashboard:

Download and install Power BI Desktop.

Open the 02_PowerBI_Dashboard.pbix file to view and interact with the full dashboard.

📧 Contact Feel free to connect with me on www.linkedin.com/in/gv-shivanjan for any questions or collaborations!