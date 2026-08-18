Diabetes Risk Analysis Dashboard

A data analytics project that predicts diabetes diagnosis likelihood using carbohydrate intake and HbA1c levels. Built with Power BI and structured for healthcare decision-making.

Why This Project?

This project demonstrates a complete analytics workflow: from exploratory data analysis through statistical insights to interactive dashboards. It's designed to answer real healthcare questions—specifically, which dietary and metabolic factors drive diabetes risk—while showing the analytical thinking behind the work.

The Problem

Diabetes affects millions, but diagnosis often comes too late. Early identification of at-risk individuals through metabolic markers (HbA1c) and dietary patterns (carbohydrate intake) could enable preventive interventions. This project tests whether we can reliably identify risk before diagnosis occurs.

Dataset & Scope
4,785 patient records across age groups (18–80)
Key variables: HbA1c levels, carbohydrate intake (grams), age, diagnosis status
HbA1c categories: Low (<5.7), Medium (5.7–6.4), High (≥6.5)—clinical thresholds for prediabetes/diabetes
Outcome: Binary diabetes diagnosis indicator
Analysis Approach

1. Data Exploration

Examined distribution of HbA1c, carb intake, and age across diagnosed vs. non-diagnosed populations. Identified that HbA1c is a strong clinical predictor, while carbohydrate intake alone shows variable correlation.

2. Risk Segmentation

Developed a risk classification system based on HbA1c categories and age groups. Found that diagnosis rates increase significantly in older populations with elevated HbA1c, enabling targeted stratification.

3. Pattern Discovery
High HbA1c (≥6.5) shows strongest association with diabetes diagnosis
Age amplifies risk: 60–80 age group with high HbA1c has ~60% diagnosis rate
Carbohydrate intake alone is not a strong predictor; metabolic health (HbA1c) is primary driver
Dashboard Features

KPI Overview – Diagnosis rates, average HbA1c, population segments

Risk Matrix – Breakdown by age group and HbA1c category, showing diagnosis prevalence

Carbohydrate Analysis – Explores relationship between intake and HbA1c; scatter plots reveal patterns

Demographic Breakdown – Age-stratified insights for public health targeting

Technical Architecture

Data Processing: CSV ingestion with standardized age grouping and risk categorization
Visualization: Power BI with interconnected visuals and dynamic slicers
Measures (DAX):

Diagnosis rate by segment
Average HbA1c by age and carb intake bins
Risk classification logic
Dynamic text for clinical thresholds
Key Insights
HbA1c is predictive. Individuals with high HbA1c (≥6.5) are 4–6x more likely to have diabetes diagnosis than those with low HbA1c.
Age matters. The 60–80 group shows elevated baseline diabetes rates; younger groups remain low unless HbA1c is high.
Carbs don't tell the whole story. Carbohydrate intake varies widely within diagnosis groups, suggesting other lifestyle factors (exercise, sleep, stress) play equal or greater roles.
Actionable segments. Medium HbA1c (5.7–6.4) represents a prediabetic window—individuals here are candidates for preventive intervention.
What This Shows
SQL/Data Processing: Structured data wrangling and segmentation
Statistical Thinking: Understanding clinical thresholds, correlation vs. causation
Dashboard Design: Clear visual hierarchy, appropriate chart selection, interactivity
Business Communication: Translating analysis into decisions (who to intervene, when, how)
Domain Knowledge: Familiarity with healthcare metrics and public health context
How to Use
Open Diabetes.pbix in Power BI Desktop or Power BI Service
Review the diabetes.csv for raw data structure
Navigate dashboards using age group and HbA1c category slicers
Hover over visuals for tooltips explaining metrics and clinical significance
