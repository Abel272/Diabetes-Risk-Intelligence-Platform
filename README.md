# Carbohydrate Intake & Metabolic Health Analysis

A comprehensive Power BI dashboard analyzing the relationship between daily carbohydrate intake and long-term biological health markers using NHANES public health survey data.

## Project Overview

This project investigates potential correlations between dietary carbohydrate consumption and a key metabolic health indicator across different demographic groups. Through structured data analysis and visualization, it translates complex health survey datasets into actionable insights for public health storytelling.

## Key Findings

- **Short-term vs. Long-term Measures**: Single-day carbohydrate intake shows near-zero correlation with longer-term biological markers, highlighting the importance of sustained dietary patterns over isolated measurements
- **Age Group Segmentation**: Distinct metabolic patterns emerge across age cohorts, requiring tailored analytical approaches
- **Clinical Risk Stratification**: Clear segmentation of population risk profiles enables targeted public health interventions

## Data Source

**NHANES (National Health and Nutrition Examination Survey)**
- Publicly available U.S. health and nutrition data
- Comprehensive demographic, dietary, and clinical measurements
- Enables population-level health trend analysis

## Dashboard Components

### 1. **KPI Summary**
   - Overall population metrics
   - Key performance indicators at a glance

### 2. **Benchmarking Matrix**
   - Risk classification framework
   - Comparative analysis across segments

### 3. **Contribution Analysis**
   - Age group contribution to aggregate metrics
   - Segment-level performance tracking

### 4. **Scatter Plot Analysis**
   - Correlation visualization
   - Individual-level data exploration

## Technical Architecture

### DAX Measures
Organized into display folders for maintainability:
- **Classification**: Risk categorization and segmentation logic
- **Risk Analysis**: Quantitative risk scoring and thresholds
- **Age Group Comparison**: Cross-cohort analytical measures
- **Correlation**: Statistical relationship calculations
- **Utilities/Dynamic Text**: Support functions and dynamic labeling

### Visual Design
- Professional, clean aesthetic focused on clarity
- Color-coded risk segments for quick interpretation
- Interactive filters for exploratory analysis

## Requirements

- **Power BI Desktop** or **Power BI Service**
- Access to NHANES public data sources
- Basic understanding of public health data structures

## How to Use

1. **Load the Data**
   - Import NHANES datasets into Power BI
   - Connect to the data source using the provided queries

2. **Explore the Dashboard**
   - Navigate between report pages
   - Use slicers to filter by age group, risk segment, or other dimensions
   - Hover over visuals for detailed tooltips

3. **Interpret the Findings**
   - Distinguish between snapshot measures (single-day intake) and cumulative markers
   - Review benchmarking matrix for risk stratification insights
   - Use age group comparisons to identify population subgroups

## File Structure

```
├── README.md                 # This file
├── Dashboard.pbix            # Power BI report file
├── Data/                     # NHANES data sources
└── DAX_Measures/             # Measure definitions and documentation
```

## Analytical Approach

This project emphasizes **analytical storytelling** — translating statistical findings into narrative context for stakeholders. Key principles:

- **Precision in Language**: Clearly distinguish between short-term measures (single-day intake) and long-term biomarkers
- **Contextual Analysis**: Present metrics within demographic and clinical frameworks
- **Actionable Segmentation**: Risk classification enables targeted interventions

## Findings & Insights

### Primary Insight
The lack of strong correlation between single-day carbohydrate intake and long-term biological markers suggests that:
- Sustained dietary patterns matter more than isolated daily measurements
- Public health interventions should emphasize habit formation over single-day compliance
- Multiple dietary and lifestyle factors contribute to metabolic health

### Segment-Specific Observations
Age groups demonstrate distinct metabolic responses to carbohydrate intake, indicating the need for age-stratified public health messaging and clinical guidelines.

## Contributing

This is a reference project for public health analytics. Contributions, improvements, and adaptations for different health datasets are welcome.

## License

This project uses NHANES public data, which is in the public domain. The dashboard methodology and DAX architecture are available for educational and analytical purposes.

## Author

Data Analyst specializing in public health survey analysis and clinical risk segmentation using Power BI.

## Contact & Questions

For questions about methodology, data interpretation, or dashboard implementation, please open an issue in this repository.

---

**Last Updated**: August 2026  
**Data Source**: NHANES (National Health and Nutrition Examination Survey)  
**Tools**: Power BI, DAX
