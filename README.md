# Marketing Campaign Performance Analysis: Tech-Savvy Solutions

A comprehensive end-to-end Marketing Campaign Analytics solution developed using Power BI, featuring Excel-driven exploratory analysis, robust star schema data modeling, centralized DAX measure optimization, short-term predictive forecasting, and executive-focused performance optimization dashboards designed to drive data-driven decision-making.

# 📑 Table of Contents

* [Overview](#overview)
* [Live Interactive Dashboard](#live-interactive-dashboard)
* [Business Context](#business-context)
* [Project Objectives](#project-objectives)
* [Business Questions](#business-questions)
* [Dataset Description](#dataset-description)

  * [Structure](#structure)
  * [Dataset Characteristics](#dataset-characteristics)
  * [Data Dictionary](#data-dictionary)
* [Tools & Technologies](#tools--technologies)
* [Project Execution Workflow](#project-execution-workflow)

  * [Phase 1: Data Ingestion](#phase-1-data-ingestion)
  * [Phase 2: Data Cleaning & Transformation](#phase-2-data-cleaning--transformation)
  * [Phase 3: Exploratory Data Analysis (Excel)](#phase-3-exploratory-data-analysis-excel)
  * [Phase 4: Semantic Data Modeling (Power BI)](#phase-4-semantic-data-modeling-power-bi)
  * [Phase 5: Measure Layer Design](#phase-5-measure-layer-design)
  * [Phase 6: Dashboard Wireframing](#phase-6-dashboard-wireframing)
* [Dashboard Breakdown](#dashboard-breakdown)

  * [Page 1 – Overview](#page-1--overview)
  * [Page 2 – Customer Growth & Acquisition](#page-2--customer-growth--acquisition)
  * [Page 3 – Trend & Predictive Insights](#page-3--trend--predictive-insights)
  * [Page 4 – Executive Optimization Summary](#page-4--executive-optimization-summary)
* [Forecasting Approach](#forecasting-approach)
* [Bookmarks Navigation & Custom buttons](#bookmarks-navigation--custom-buttons)
* [Overall Strategic Recommendation](#overall-strategic-recommendation-summary)
* [Business Impact](#business-impact)
* [Limitations](#limitations)
* [Future Improvements](#future-improvements)
* [Conclusion](#conclusion)
* [Author](#author)
* [Contact](#contact)

## Overview

What truly happens after marketing spend is deployed? Does it generate measurable revenue and sustainable growth, or just surface-level engagement metrics?

This project delivers a complete end-to-end Marketing Performance Analytics and Optimization solution built in Power BI. Starting with data cleaning, transformation, preprocessing, and exploratory analysis in Excel, the project progresses through scalable star schema modeling, optimized DAX development, and structured dashboard wireframing before culminating in four executive-ready dashboards.

The final solution connects marketing spend, acquisition efficiency, revenue performance, and trend stability into a structured decision-making framework, supported by short-term forecasting and strategic optimization recommendations.

## Live Interactive Dashboard

👉 To view the interactive dashboard and explore its full functionality: 

[Click here](https://www.novypro.com/profile_about/1768603691117x499853414232449100?Popup=memberProject&Data=1772609122232x542527365498012900)

## Business Context

Marketing teams face critical questions:

* Is our campaign truly profitable?

* Which channels deliver the highest return?

* Are we acquiring customers efficiently?

* Is performance stable over time?

* Where should we reallocate the budget for maximum impact?

This project consolidates campaign data into a unified BI solution to support data-driven marketing decisions.

## Project Objectives

The key objectives were to:

* Evaluate overall marketing ROI and profitability

* Analyze acquisition efficiency across channels and segments

* Identify performance trends and stability over time

* Develop short-term revenue forecasting

* Provide strategic optimization recommendations

* Build a scalable star schema semantic model

* Deliver executive-ready interactive dashboards

## Business Questions

The analysis was guided by the following questions:

* What is the total return generated from marketing spend?

* Which channels and campaign types drive the highest revenue?

* How efficient is customer acquisition across segments?

* Does higher acquisition quality translate into higher revenue?

* Is performance stable, seasonal, or declining?

* What optimization actions should leadership prioritize?

## Dataset Description

### Structure
The dataset represents structured marketing campaign performance data. Each row captures campaign-level metrics, including:

* Company
* Campaign_Type
* Target_Audience
* Duration
* Channels_Used
* Conversion_Rate
* Acquisition_Cost
* ROI
* Location
* Language
* Clicks
* Impressions
* Engagement_Score
* Customer_Segment
* Date

Raw Dataset - Sample
<img width="1319" height="550" alt="Raw Dataset (Sample)" src="https://github.com/user-attachments/assets/d5698637-0c44-4841-9ab4-65a08bf52636" />

### Dataset Characteristics:

* Granularity: Campaign-level performance

* Size: ~200,000 rows

* Time Coverage: Multi-period marketing activity

### Data Dictionary 
To better understand the structure of the dataset. I created a simple data dictionary to describe each column:
<img width="1348" height="366" alt="Screenshot 2026-03-04 021547" src="https://github.com/user-attachments/assets/42abbf5d-f513-452d-80e0-7d08b930593a" />

## Tools & Technologies

* Microsoft Excel (EDA Phase)

* Power BI Desktop

* Power Query (Data Cleaning, Transformation & Preprocessing)

* DAX

* Star Schema Modeling

* Time Intelligence

* Forecasting (Power BI Analytics)

* PowerPoint (Wireframing)

* Bookmarks Navigation & Custom buttons

* Data Visualization & Storytelling

## Project Execution Workflow
This project followed a structured BI lifecycle to ensure analytical reliability and storytelling clarity.

### Phase 1: Data Ingestion
Imported the raw marketing campaign dataset into Power BI (Power Query)

<img width="1366" height="721" alt="Get Data 01" src="https://github.com/user-attachments/assets/25a3c7f8-c772-47f1-a3e9-d8e98faff57c" />

<img width="682" height="662" alt="Get Data 02" src="https://github.com/user-attachments/assets/2528b7b8-5923-4299-b942-b69f5fef4b4c" />

<img width="880" height="660" alt="Data Ingestion 03" src="https://github.com/user-attachments/assets/92869263-8a4c-46f6-9f65-5fc149e631c6" />

### Phase 2: Data Cleaning & Transformation

Cleaned and transformed the data using Power Query. The following processes were carried out to ensure that the data is well prepared fpr effective analysis:

* Removed duplicates and irrelevant fields

* Standardized column names

* Corrected data types (Date, Numeric, Currency, Percentage)

* Created a centralized Fact Table and an additional dimensions table

* Generated Date Dimension table

* Created surrogate Date ID where applicable

* Ensured consistent formatting across categorical fields

<img width="1366" height="721" alt="01 Data Preparation" src="https://github.com/user-attachments/assets/1cd0453c-c7d6-4512-a4da-e186f56ac7be" />

<img width="1366" height="721" alt="02 Data Preparation" src="https://github.com/user-attachments/assets/987a387e-b033-4532-b6db-966b4f023d24" />

<img width="1366" height="721" alt="03 Data Preparation" src="https://github.com/user-attachments/assets/c2da03f6-dd53-4f45-a1c3-1e1ca167cd38" />

<img width="1366" height="721" alt="04 Data Preparation" src="https://github.com/user-attachments/assets/182bfc8a-c836-4a95-878f-b22fcb662306" />

**Why This Was Important:**

* Prevented aggregation errors in Power BI

* Ensured correct relationship modeling

* Enabled accurate time intelligence calculations

* Improved overall model performance

This phase ensured that the dataset was analytics-ready before modeling.


### Phase 3: Exploratory Data Analysis (Excel)

In this phase, Exploratory Data Analysis was conducted in Microsoft Excel to validate data quality, understand performance patterns, and prepare the dataset for structured modeling in Power BI.

Key KPIs such as Total Spend, Revenue, Clicks, Impressions, ROI, and Conversion Rate were verified using pivot tables and summary calculations to ensure logical aggregation and consistency. Performance was analyzed across campaign type, marketing channel, target audience, and location to identify trends, profitability distribution, and segment-level performance differences.

Additionally, preliminary data modeling was performed by organizing the dataset into structured tables, standardizing fields, and validating how performance metrics aggregated across business dimensions.

This phase ensured data integrity, clarified performance patterns, and informed the structural design of the Power BI dashboards, preventing assumption-driven modeling and enabling a business-focused analytical approach.

<img width="985" height="579" alt="Screenshot 2026-02-12 203934" src="https://github.com/user-attachments/assets/e73ed674-fa09-4af7-b144-7eb22a7bbbc8" />

<img width="1239" height="555" alt="Screenshot 2026-02-15 151012" src="https://github.com/user-attachments/assets/35675eb5-9ad3-4e7f-bb8e-943a5f2fd690" />

<img width="455" height="434" alt="Screenshot 2026-02-15 151035" src="https://github.com/user-attachments/assets/a8f4e32a-2d13-452b-8f19-f944b7863a3a" />

### Phase 4: Semantic Data Modeling (Power BI)

A structured star schema model was implemented to improve scalability and analytical performance.

**Model Components:**

* Centralized Fact Table

* Campaign Dimension Table

* Company Dimension Table

* Date Dimension Table

* Segment, Location, and Campaign Type attributes

<img width="1280" height="720" alt="Fact x Company DIM Table" src="https://github.com/user-attachments/assets/560e9ca6-862a-4e62-a578-cb0898c36782" />

<img width="1280" height="720" alt="Campaign x Date DIM Table" src="https://github.com/user-attachments/assets/eb4ebb7f-4776-491a-9db4-5d67234b1da3" />

**Modeling Decisions:**

* Relationships were structured using single-direction filtering to maintain clarity and avoid ambiguity.

* Used Date Dimension for time intelligence

* Optimized model for performance and scalability

<img width="1004" height="496" alt="Screenshot 2026-02-12 224703" src="https://github.com/user-attachments/assets/64d758ef-781a-478d-9fc2-4f9054701ee0" />

This model supports time intelligence, segmentation analysis, and scalable measure development.

### Phase 5: Measure Layer Design

In this phase, I created a centralized measure layer to separate business logic from raw data and enable reusable KPI calculations. This approach improved readability, maintainability, and overall performance of the Power BI model.

#### Key Purpose:

* Store all calculated measures in a single layer

* Separate business logic from raw data tables

* Improve readability and maintainability of DAX formulas

* Enable reusable KPI calculations across dashboards

<img width="534" height="348" alt="Calculated Measures Table" src="https://github.com/user-attachments/assets/ff030c62-4f82-4ef0-b973-e38638e564fe" />

#### DAX Development

I developed optimized DAX measures to support dynamic and filter-responsive analytics. Measures included:

* Total Spend (Acquisition Cost)

* Total Revenue

* Profit

* Average ROI

* Clicks Through Rate (CTR)

* Cost Per Click (CPC)

* Profit Margin

* Conversion Rate

* Month-over-Month Growth

I also implemented time intelligence functions to support trend analysis and short-term forecasting.

The images below show snapshots of the created DAX measures:

<img width="634" height="501" alt="DAX Measures  01" src="https://github.com/user-attachments/assets/9b739643-8ac5-44a1-b8f5-272a5a3d2c08" />

<img width="670" height="498" alt="DAX Measures  02" src="https://github.com/user-attachments/assets/6ede1c03-e9f8-4bae-a694-6e25196073ec" />

<img width="667" height="498" alt="DAX Measures  03" src="https://github.com/user-attachments/assets/cc763dbc-c84a-41be-94c0-b8f57ab5a379" />

<img width="668" height="503" alt="DAX Measures  04" src="https://github.com/user-attachments/assets/7af0646a-48e7-4387-bb90-cf433e4d13ce" />

<img width="673" height="501" alt="DAX Measures  05" src="https://github.com/user-attachments/assets/098f21db-8076-40b4-9418-fb8d34c46846" />

<img width="673" height="498" alt="DAX Measures  06" src="https://github.com/user-attachments/assets/5032ad28-293e-4259-b45f-749fc4504e66" />

<img width="697" height="502" alt="DAX Measures  07" src="https://github.com/user-attachments/assets/0e560929-b98e-4c25-bd2b-d15c26d5fc71" />

<img width="695" height="498" alt="DAX Measures  08" src="https://github.com/user-attachments/assets/4f936488-f4f7-4d59-98f8-fae02ab9b532" />

<img width="698" height="184" alt="DAX Measures  09" src="https://github.com/user-attachments/assets/c4bc5e8d-5404-42b9-9d18-a9151fe73f46" />

### Phase 6: Dashboard Wireframing

Before building in Power BI:

* Four dashboard pages were wireframed in PowerPoint

* KPI hierarchy was defined

* Visual placement was structured logically

* Business questions were mapped directly to visuals

This ensured executive-level storytelling and avoided visual clutter.

<img width="1280" height="720" alt="Slide1" src="https://github.com/user-attachments/assets/e0906b19-de64-437a-ae5f-f9448272169f" />

<img width="1280" height="720" alt="Slide2" src="https://github.com/user-attachments/assets/1b56e1a4-9300-4f31-983b-41d5bc0f8d7d" />

<img width="1280" height="720" alt="Slide3" src="https://github.com/user-attachments/assets/16527c60-e7d4-45a4-812d-c6fb42600ad5" />

<img width="1280" height="720" alt="Slide4" src="https://github.com/user-attachments/assets/85f492ea-836c-4f22-a77e-1ef4c68fc5b3" />

## Dashboard Breakdown

### Page 1 – Overview
<img width="819" height="465" alt="Page 1" src="https://github.com/user-attachments/assets/5bbc07bc-64a9-4e47-8d77-da59d3bf8a1e" />

#### Key Insights

* The overall campaign delivered strong financial performance, generating $15.02bn in revenue from $2.50bn in spend, resulting in an average ROI above 500%. This confirms that the marketing strategy is highly profitable and operationally efficient.

* Performance across channels is relatively balanced, with no single platform disproportionately driving revenue. This suggests a diversified channel strategy rather than over-reliance on one medium. However, slight differences in revenue contribution indicate marginal efficiency advantages among top-performing channels.

* At the company and regional levels, revenue distribution remains consistent, indicating that campaign execution is standardized and scalable across business units and locations.

#### Recommendations

Given the consistently high ROI, the focus should shift from profitability validation to incremental optimization. Budget allocation can be fine-tuned toward the marginally higher-performing channels to enhance total return without increasing overall spend.

Additionally, a deeper review of the slightly outperforming company or channel strategies may reveal tactical advantages that can be replicated across other units

 ### Page 2 – Customer Growth & Acquisition

<img width="818" height="461" alt="Page 2" src="https://github.com/user-attachments/assets/87d2f730-ca24-49f5-ac38-af7a7c78a4e7" />

#### Key Insights

* The campaign demonstrates strong acquisition performance, with 1bn impressions, 110M clicks, and a 9.98% CTR, indicating effective audience targeting and engagement.

* Cost efficiency remains stable, with a Cost Per Click (CPC) of $22.74 and a profit margin above 83%, confirming that acquisition costs are well controlled relative to revenue generated.

* Customer segment performance is evenly distributed, suggesting broad market appeal rather than reliance on a single audience group.

* The positive relationship between acquisition cost and ROI indicates that higher-value segments may justify slightly higher investment.

#### Recommendations

* Optimization should focus on segment-level efficiency refinement rather than expansion.

* High-performing segments identified in the ROI-to-cost relationship should receive prioritized budget adjustments.

* With engagement already strong, performance improvements should target conversion optimization and funnel efficiency, ensuring that traffic translates into higher revenue without disproportionately increasing acquisition cost.

### Page 3 – Trend & Predictive Insights

<img width="817" height="461" alt="Page 3" src="https://github.com/user-attachments/assets/2fddd334-9779-4d71-b3cd-ebaad8cfd95c" />

#### Key Insights

* Revenue and spend demonstrate a stable upward trajectory with moderate monthly fluctuations. Despite short-term dips (e.g., early-year decline), overall performance quickly recovers, indicating resilient campaign effectiveness.

* The relationship between acquisition score and revenue shows a positive correlation, confirming that higher-quality acquisition efforts translate into stronger revenue outcomes.

* The three-month revenue forecast projects continued gradual growth, suggesting sustained campaign momentum if current strategies are maintained.

#### Recommendations

* Given the stability and positive trajectory, the focus should be on maintaining consistency rather than aggressive expansion. Budget discipline and performance monitoring should continue to preserve growth stability.

* Since acquisition score aligns positively with revenue, optimization efforts should prioritize improving targeting quality and audience relevance rather than merely increasing spend.

* The short-term forecast supports steady performance expectations; therefore, resource planning and budgeting decisions can be made with moderate confidence for the next quarter.

 ### Page 4 – Executive Optimization Summary

<img width="820" height="463" alt="Page 4" src="https://github.com/user-attachments/assets/cb836165-99c6-4a8f-b8cd-ec51407705d8" />

#### Key Insights

* Campaign performance remains strong across campaign types, with Influencer and Search campaigns slightly outperforming others in profit contribution.

* Engagement score analysis shows that medium engagement segments generate the highest profit contribution, suggesting an optimal balance between reach and conversion efficiency.

* Revenue distribution across campaign durations is relatively even, though 30-day campaigns marginally outperform others, indicating that moderate campaign length may be most effective.

* Target audience revenue is evenly distributed, confirming broad demographic appeal without heavy dependency on a single group.

#### Recommendations

* Future optimization should prioritize high-ranking campaign types, particularly Influencer and Search, while maintaining diversified allocation across other channels.

* Given the strong performance of medium engagement score segments, campaign design should aim to replicate the characteristics driving that engagement level.

* Thirty-day campaign duration appears strategically efficient; therefore, future campaigns may standardize around this timeframe unless specific objectives require deviation.

Overall, performance optimization should focus on incremental efficiency improvements rather than structural changes, as the campaign framework is fundamentally sound.

## Forecasting Approach

* A short-term (3-month) revenue forecast was applied using Power BI’s built-in analytics forecasting model.

* Forecast horizon was intentionally limited to ensure reliability and avoid speculative long-term projections.

## Bookmarks Navigation & Custom buttons

Interactive navigation was implemented using Power BI bookmarks and custom-designed buttons to enhance user experience and improve report usability.

Implementation Highlights:

* Created bookmarks to control page views, filter states, and visual visibility

* Designed custom navigation buttons for seamless movement across dashboard pages

* Enabled dynamic show/hide effects for a cleaner executive presentation

* Improved storytelling flow and guided analytical exploration

<img width="242" height="511" alt="Bookmarks Snapshot" src="https://github.com/user-attachments/assets/1a90ee8b-c828-4074-87f4-b420d86d3e3f" />

**Business Value:**

This approach transforms the report from a static dashboard into a guided analytical experience, allowing stakeholders to interact intuitively with insights while maintaining a structured decision-making flow.


## Overall Strategic Recommendation (Summary)

The marketing campaign is financially strong, with revenue significantly outperforming spend and ROI consistently above 500%, indicating a scalable and well-structured strategy. Performance is balanced across channels, segments, and regions, suggesting operational stability rather than reliance on a single driver.

Moving forward, the focus should shift from aggressive expansion to strategic optimization. Budget allocation should be refined toward the highest-performing segments, while improving audience targeting quality and conversion efficiency instead of simply increasing volume.

High-performing campaign structures, particularly moderate-duration campaigns, should be standardized as best-practice benchmarks. At the same time, short-term revenue forecasting and continuous performance monitoring should remain in place to quickly identify shifts in trends or diminishing returns.

Overall, the strategy should prioritize efficiency, precision, and sustainable growth.

## Business Impact

This solution enables stakeholders to:

* Monitor ROI in real time

* Identify channel-level efficiency

* Detect trend stability

* Support budget allocation decisions

* Improve marketing optimization strategy

## Limitations

* Analysis is primarily descriptive with short-term forecasting.

* External market factors were not included.

* Dataset assumes internal metric consistency.

## Future Improvements

* Advanced predictive modeling

* Customer lifetime value modeling

* Marketing mix modeling

* Budget simulation scenario analysis

## Conclusion

The process began with detailed exploratory data analysis in Excel, where trends, relationships, and structural patterns were identified. The workflow then progressed into Power BI for semantic data modeling and advanced analytics. A scalable star schema was implemented and supported by a centralized DAX measure layer to ensure consistency, reusability, performance efficiency, and analytical accuracy.

This project demonstrates the ability to:

* Execute comprehensive exploratory data analysis

* Design and implement scalable semantic data models

* Develop optimized and reusable DAX measures

* Build executive-ready, interactive dashboards

* Translate analytical findings into strategic business recommendations

Overall, this solution demonstrates how structured data modeling, optimized measure design, and interactive dashboard storytelling can transform marketing data into strategic decision support.

## Author

Ibrahim Abdulrasaq

Data Analyst | BI Specialist

## Contact

If you’d like to discuss this project or collaborate on data analytics work, feel free to connect.

🔗 [Email](mailto:ibrahimabdulrasaqademola2017@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/ibrahim-abdulrasaq/)

🔗 [Github](https://github.com/ibrahimabdulrasaq)



