# Workforce-Analysis

### Project Title
#### Workforce 360: Comprehensive HR Analytics for Employee Engagement & Retention

#### Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Tools](#tools)
- [Data Extraction](#data-extraction)
- [Data Cleaning](#data-cleaning)
- [Data Visualization](#data-visualization)
- [Data Insights and Recommendation](#data-insights-and-recommendation)
- [Limitations](#limitations)

### Project Overview
This project explores the relationship between employee engagement and retention using real-world HR data, by analyzing employee demographics, attrition patterns, compensation structures, gender equality and career progression. The goal is to uncover actionable insights that help organizations improve employee experience and reduce attrition.

### Data Set
Source: Public Domain
Size:

### Objectives
- Analyze employee demographics to identify patterns and trends across the organization.

- Assess career growth and turnover by evaluating key factors such as tenure, role progression, and exit patterns within the provided data.

- Evaluate compensation, pay equity, location, and age in relation to turnover rates and employee satisfaction across various departments and roles.

### Tools
- SQL - Data Extraction 
- Excel - Data Cleaning  
  - [View here](https://1drv.ms/x/c/29832ebdc9e8d616/EZUHp16IEmdOtewSd4ulvh0BqXiPG3RcNWIH4atmWiX-Ng?e=suqtku)
- PowerBI - Data Visualization and Analysis

### Data Extraction
Extracted csv/text data type using SQL. The Employee_table created was extracted to Excel for data cleaning.

### Data Cleaning
In the Data Cleaning phase, the following task was performed
- Data loading and inspection
- Data Cleaning and formatting
- Formatting Duplicates
- Conducted initial exploratory analysis using pivot tables and charts
  
### Data Visualization 
- Imported cleaned data to create interactive dashboards
- Built visuals like bar charts, line graphs, maps, and KPIs to showcase key insights
- Applied DAX formulas for calculated fields and measures
  
### Data Insights and Recommendation

#### Demographics
- The predominant race across the company is White.
- Over 50% of employees have a background in Technology and IT-related education.
- Females have been the dominant gender over time, currently making up 46% of the workforce. Non-binary representation remains low and steady.
- The 20–30 age group is the most represented, indicating the company mainly hires younger employees. This, combined with promotion patterns, suggests that internal promotion may not be the primary method for filling new roles.

#### **Performance Analysis**

#### Salary Trends
_Sales Department_
  - Held the highest average salary in early years.  
  - Saw a significant dip in **2017**, followed by a short recovery. Salaries are now trending down again.
  
_Technology Department_
  - Largest headcount.  
  - Major salary drop in **2016**, recovered afterward, but now showing signs of decline again.
  
_HR Department_
  - Most volatile.  
  - Several salary dips over the years, but a **strong and consistent increase** since **2020**.

#### **Promotion**
- Technology Department had the highest number of promotions.
- Promotions across male and female staff have fluctuated. 
- A surge in female promotions occurred in recent years, though males held the highest promotion rate overall last year.
- Non-binary and "Prefer not to say" categories saw minimal promotions.

#### Attrition
- High attrition observed in:  
  - Data Scientist 
  - Sales Executive  
  - Software Manager  
  - Sales Rep
- These roles have low average salaries despite high overtime, possibly contributing to dissatisfaction and turnover.

#### Recommendations

- Review Compensation:  
  Evaluate salary structures in the Technology Department and high-attrition roles. Consider adding benefits or bonuses to improve retention.
  
- Link Pay to Performance
  Collect updated data to compare performance metrics vs. salary to ensure fairness and reward top performers.

- Hire Across Age Groups  
  Increase recruitment of employees aged 30+ and 50+. Older employees can enhance work ethic, bring experience, and improve team stability and retention.

### Limitations
While the dataset provided valuable insights into departmental trends, it had some key limitations:

Lack of Contextual Data:
The dataset did not include critical variables such as performance reviews, departmental budgets, or company financials, which could explain the reasons behind salary fluctuations.

No Business Impact Metrics:
There was no data on how salary trends impacted company performance, such as employee satisfaction, productivity, or turnover cost.

Missing HR Strategy Inputs:
The dataset lacks information on HR policies, management decisions, or promotion criteria, limiting the ability to fully understand the drivers behind attrition and promotions.
