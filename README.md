# Planday Data Analyst Task

This repository contains a data analysis project for Planday, focusing on understanding customer behavior and conversion patterns. The data is organized in three levels: raw data (Bronze), cleaned data (Silver), and analysis-ready data (Gold).

## Project Structure

```
├── Bronze/
│   └── DA task.csv (23MB) - Raw data file
├── Silver/
│   └── events_clean.csv (15MB) - Cleaned events data
├── Gold/
│   ├── activity_counts.csv (72KB) - Activity summary by organization
│   ├── dim_date.csv (5.1KB) - Date information
│   ├── dim_org_summary_date.csv (4.5KB) - Organization data by date
│   └── org_summary.csv (133KB) - Organization summary data
├── Planday Data Analyst Maternity Cover Task 2025.pdf - Task requirements
├── Question 3 - additional data.pdf - My answer to the question 3 in the task file.
├── Planday_Data_Analysis.ipynb - Jupyter notebook with analysis
├── Planday_Dashboard.pbix - Power BI dashboard
└── README.md
```

## What This Project Is About

This analysis helps understand how trial users become paying customers. We track what users do in the platform and try to figure out what makes them decide to pay for the service.

## Project Deliverables

### Jupyter Notebook (Planday_Data_Analysis.ipynb)
- **Data Exploration**: Started by reading and understanding the data structure
- **Data Cleaning**: Cleaned and prepared the data for analysis
- **Conversion Analysis**: Analyzed trial-to-paid conversion patterns
- **Feature Analysis**: Studied which activities correlate with conversion
- **Time Analysis**: Examined conversion timing and early engagement patterns

### Power BI Dashboard (Planday_Dashboard.pbix)
The dashboard contains multiple pages with comprehensive analysis:

**Overview Page:**
- **Key Metrics Cards**
- **Trial Status Flow**
- **Organizations Journey**
- **Active Organizations Trend**
- **Conversion Rate Trend**
- **Trial Week Activity**

**Event Date (User Activity) Page:**
- **Quiet Gap Analysis**
- **Active Organizations by Date**
- **Quiet Gap Distribution**

**Trial Window Page:**
- **Activity Intensity by Trial Day**
- **Organization Retention**
- **Weekly Journey**

**Conversion Page:**
- **Engagement Frequency Distribution**
- **Features Used Before Purchase**
- **Conversions by Time to Buy**
- **Conversions by Days Since Trial Start**
- **Conversion Rate by Return Behavior**

**Overview 2 Page:**
- **Cadence Mix**
- **Engagement Levels**
- **Events Trend**
- **First Week Category Usage**
- **Conversion Rate by Activity**

**Pre-Purchase Behavior Page:**
- **Recent Popular Activities**
- **Activities After Return**
- **Feature Adoption Timeline**
- **Top Activities Before Purchase**

## Key Questions to Answer
- What's the overall conversion rate?
- Which features do paying customers use most?
- How important is early engagement (first week)?
- What's the average time to conversion?
- Are there any patterns in when people convert?

---

*This project helps understand what makes trial users become paying customers by analyzing their behavior patterns.* 
