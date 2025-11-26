📊 Insurance Risk & Claims Analysis – Power BI Dashboard

A complete end-to-end Insurance Analytics Dashboard built using Power BI, designed to provide deep insights into policyholder behavior, car characteristics, claim frequency, risk indicators, and demographic patterns.

This report consolidates scattered policy and claim data into an interactive, visually rich, and decision-focused analytics solution.

🚀 Project Overview :

The goal of this project is to help an insurance company understand:

Claim severity & frequency

Customer risk profiles

Policyholder demographic patterns

Vehicle-related risk factors

Geographic risk zones

Using the centralized Power BI dashboard, stakeholders can identify high-risk groups, optimize pricing, and make data-driven decisions.

Business Requirements Reference: 

Business Requirements


Domain Document Reference: 

Domain Doc

📂 Project Files Included
File	Description
insurance_risk.pbix	Complete Power BI report
insurance_policies_data.xlsx	Raw dataset used for modelling
Business Requirements.docx	KPI definitions, chart requirements, stakeholder needs
Domain Doc.docx	Field-level explanation, dataset meaning, business context
🧩 Data Model & ETL (Power Query)
✔ Data Transformations

Cleaned and standardized categorical fields

Extracted Age from Birthdate

Created Age Groups, Income Bands, Car Age buckets

Removed inconsistencies & deduplicated policy IDs

Ensured correct data types for modeling

✔ Star Schema

Fact Table: Claims & Policy Metrics

Dimension Tables: Customer, Vehicle, Geography, Demographics

This ensures optimized performance and better DAX functionality.

📌 Key KPIs

As required in the business requirements 

Business Requirements :

Total Policies

Total Claim Amount

Claim Frequency

Average Claim Amount

Gender-wise Total Policies

These KPIs drive risk assessment and portfolio performance analysis.

📈 Visualizations Included

All visuals are aligned with the specification in the Business Requirements document.
The dashboard includes:

Demographic Insights

Age Group Distribution (Histogram)

Education-Level Breakdown (Pie Chart)

Gender-wise Policy Count

Education × Marital Status (Matrix Heatmap)

Vehicle Insights

Car Make vs Claims (Bar Chart)

Car Year (Area Chart)

Car Use (Donut Chart)

Risk & Behavioral Insights

Coverage Zone Analysis (Donut Chart)

Kids Driving Impact (Ribbon Chart)

Claim Frequency & Claim Amount segments

All definitions of attributes are based on the Domain Document 

Domain Doc :

📉 DAX Measures

Core measures include:

Total Policies

Total Claim Amount

Average Claim Amount

Claim Frequency

Age Group measure and bins

Vehicle Age & Segmentation measures

These measures power all dynamic visuals and filters.

🎯 Insights You Can Derive

Identify high-risk customer demographics (young drivers, low-income groups, etc.)

Detect vehicle brands/models with frequent or costly claims

Understand regional risk zones

Spot households with multiple young drivers causing higher claims

Compare how education, income, and marital status influence policy behavior

🔧 Tools & Technologies

Power BI Desktop

Power Query

DAX

Excel

Data Modelling (Star Schema)

📥 How to Use This Dashboard

Download the .pbix file from the repository

Open in Power BI Desktop

Refresh the dataset (Excel file included)

Explore insights using filters, slicers, and drill-downs

Modify data model or add new calculations as needed

⭐ Future Enhancements

Integration with SQL database

Deployment to Power BI Service

Row-Level Security (RLS)

Predictive modeling using Python/R in Power BI
