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
├── Question 3 - additional data.pdf - Additional data information
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

### PDF Files
- **Planday Data Analyst Maternity Cover Task 2025.pdf**: Contains the main task requirements and objectives
- **Question 3 - additional data.pdf**: Provides additional context and data specifications

### Power BI Dashboard (Planday_Dashboard.pbix)
The dashboard contains multiple pages with comprehensive analysis:

**Overview Page:**
- **Key Metrics Cards**: Conversion rate (21%), average time to convert (30.27 days), total events (103K), average activities per org (106.52), new users percentage (16%)
- **Trial Status Flow**: Visual funnel showing 966 total organizations → 958 completed trials → 205 converted vs 753 not converted
- **Organizations Journey**: Bar chart showing Week 1 activation (821 orgs) and converted organizations (206 orgs)
- **Active Organizations Trend**: Line chart showing monthly active organization counts
- **Conversion Rate Trend**: Monthly conversion rate trends
- **Trial Week Activity**: Percentage of active organizations during each trial week

**Event Date (User Activity) Page:**
- **Quiet Gap Analysis**: Average quiet gap for converters (22.95 days) vs non-converters (23.08 days)
- **Active Organizations by Date**: Line chart showing weekly active organization trends
- **Quiet Gap Distribution**: Histograms showing quiet gap patterns before trial end and before purchase

**Trial Window Page:**
- **Activity Intensity by Trial Day**: Area chart showing engagement levels throughout the 30-day trial period
- **Organization Retention**: Table showing retention rates over months after trial
- **Weekly Journey**: Bar chart tracking new vs carryover trial organizations by week

**Conversion Page:**
- **Engagement Frequency Distribution**: Horizontal bar chart showing activity usage patterns
- **Features Used Before Purchase**: Most common activities in the days leading to conversion
- **Conversions by Time to Buy**: Histogram showing conversion timing distribution
- **Conversions by Days Since Trial Start**: Timeline of when conversions occur
- **Conversion Rate by Return Behavior**: Line chart showing conversion rates based on return patterns

**Overview 2 Page:**
- **Cadence Mix**: Stacked bar chart showing daily/weekly/irregular usage patterns by conversion status
- **Engagement Levels**: Distribution of weakly engaged (48%), engaged (33%), and very engaged (19%) users
- **Events Trend**: Monthly event count trends
- **First Week Category Usage**: Feature adoption in the first week of trial
- **Conversion Rate by Activity**: Success rates for different activity categories

**Pre-Purchase Behavior Page:**
- **Recent Popular Activities**: Most frequent activities before purchase
- **Activities After Return**: What users do when they come back to the platform
- **Feature Adoption Timeline**: Average day in trial when different features are adopted
- **Top Activities Before Purchase**: Detailed breakdown of pre-conversion activities

## Key Questions to Answer
- What's the overall conversion rate?
- Which features do paying customers use most?
- How important is early engagement (first week)?
- What's the average time to conversion?
- Are there any patterns in when people convert?

---

*This project helps understand what makes trial users become paying customers by analyzing their behavior patterns.* 