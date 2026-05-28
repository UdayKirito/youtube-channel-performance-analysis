# YouTube Channel Performance Analysis: Growth, Engagement, and Global Trends

## Project Overview

This project analyzes global YouTube channel performance to understand what drives channel success across subscribers, views, content categories, estimated earnings, and country-level factors.

The goal was to identify patterns behind high-performing YouTube channels and translate those findings into business-friendly insights for creators, marketers, and digital media teams.

This was completed as part of the **Data Visualization** coursework at **Montclair State University**.

## Business Problem

YouTube success is often measured by subscribers, views, and revenue, but it is not always clear which factors contribute the most to growth and monetization.

This project explored the following questions:

- What differentiates top-performing YouTube channels from lower-performing channels?
- Which content categories generate the strongest engagement and earnings?
- Do country-level economic indicators influence YouTube channel growth?
- How are subscribers, views, uploads, and estimated earnings related?

## Dataset

The analysis used the **Global YouTube Statistics 2023** dataset from Kaggle.

The dataset included channel-level, content-level, and country-level variables such as:

- Subscribers
- Video views
- Upload count
- Estimated yearly earnings
- Content category
- Country
- Population
- Urban population percentage
- Gross tertiary education enrollment percentage
- Unemployment rate

The cleaned dataset contained approximately **830 records** and **28 variables** after preprocessing.

## Tools & Technologies

- **Python** – data cleaning, preprocessing, feature engineering, and statistical analysis
- **Tableau** – interactive dashboard creation and visual storytelling
- **Excel / CSV** – dataset review and preparation
- **Statistics** – correlation analysis, t-tests, ANOVA, and multiple linear regression

## Methodology

### 1. Data Cleaning & Preparation

The dataset was cleaned to remove or handle missing values in important fields such as country, category, education enrollment, unemployment rate, population, and urban population.

Additional variables were created to support analysis, including:

- **Performance Score** – a weighted score based on subscribers, video views, and estimated earnings
- **Performance Category** – classification of channels into top, middle, and bottom performers
- **Scaled population variables** – standardized country-level indicators for comparison

### 2. Exploratory Data Analysis

Exploratory analysis was used to understand distributions, category-level performance, and relationships between subscribers, views, uploads, and earnings.

### 3. Statistical Analysis

The project applied multiple statistical methods:

- **Correlation analysis** to measure relationships between YouTube performance metrics
- **T-tests** to compare top-performing and bottom-performing channels
- **ANOVA** to evaluate whether engagement differs significantly across content categories
- **Multiple linear regression** to test whether country-level factors explain YouTube performance

### 4. Dashboard Development

An interactive Tableau dashboard was created to communicate the results visually through charts, maps, ranking tables, and filters.

## Key Findings

### Subscriber count and video views are strongly connected

Subscriber count had a strong relationship with total video views, showing that larger audiences generally support higher engagement.

### Upload frequency alone does not guarantee success

The number of uploaded videos had a weak relationship with subscriber growth, suggesting that content quality, audience fit, and engagement matter more than simply posting more videos.

### Top performers significantly outperform bottom performers

Top-performing channels had much higher average subscribers, views, and estimated yearly earnings compared with bottom-performing channels. Statistical testing confirmed that these differences were significant.

### Entertainment and Music dominate monetization

Entertainment and Music were among the strongest categories for earnings and engagement, while categories such as Travel & Events, Science & Technology, and Nonprofits & Activism showed lower monetization in this dataset.

### Country-level economic factors had limited explanatory power

Regression analysis showed that country-level factors such as population, urban population, education enrollment, and unemployment rate did not meaningfully explain YouTube success in this dataset.

## Tableau Dashboard

Interactive dashboard:

[View Tableau Public Dashboard](https://public.tableau.com/views/UnderstandingYouTubeSuccess_AnalyzingChannelGrowthEngagementandGlobalTrends/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

The dashboard allows users to explore YouTube performance by content category, geography, subscribers, views, and earnings.

## Business Impact

This project translates raw YouTube channel data into practical insights for digital strategy:

- Helps creators understand which categories have stronger engagement and monetization potential
- Helps marketers identify high-performing content segments and global markets
- Shows that views and audience engagement are stronger indicators of success than upload volume alone
- Demonstrates how statistical analysis can validate dashboard insights

## Skills Demonstrated

- Business intelligence reporting
- KPI analysis
- Data visualization
- Dashboard storytelling
- Data cleaning and preprocessing
- Feature engineering
- Statistical hypothesis testing
- Correlation analysis
- ANOVA
- T-test
- Regression analysis
- Business insight generation

## Repository Structure

```text
youtube-channel-performance-analysis/
│
├── README.md
├── data/
│   └── Global YouTube Statistics.csv
│
├── reports/
│   ├── project_summary.md
│   ├── Final_Report_Group_7_Dobariya_Shivekar_Sharma_Eepu.docx
│   └── Project_Proposal_.docx
│
├── dashboards/
│   └── tableau_dashboard_link.md
│
└── images/
    └── dashboard_screenshot.png
```

## Project Team

- Hinkalben Dobariya
- Shubham Shivekar
- Tanya Sharma
- Uday Kumar Eepu

## Academic Context

Course: **Data Visualization**  
Institution: **Montclair State University**  
Professor: **Dr. Eyyub Kibis**

## Note

This project was completed for academic purposes using a static 2023 dataset. The findings should be interpreted as a snapshot of YouTube channel performance and not as real-time platform trends or financial advice.
