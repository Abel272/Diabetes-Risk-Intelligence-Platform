# Diabetes Risk Analysis

A data analysis project exploring the relationship between HbA1c levels, carbohydrate intake, age, and diabetes diagnosis across multiple countries.

## What's in here

- **diabetes.csv** - Dataset with ~4,800 records including HbA1c measurements, dietary intake, demographics, and diabetes diagnosis status
- **Diabetes.pbix** - Power BI dashboard for interactive exploration and visualization of the data

## The data

The dataset includes:
- **HbA1c levels** - 3-month glucose average (key diabetes indicator)
- **Carbohydrate intake** - Daily carb consumption in grams
- **Age groups** - Ranges from 18 to 80+
- **Countries** - International data for cross-regional comparison
- **Diabetes diagnosis** - Binary outcome variable

Each HbA1c value is categorized (Low, Medium, High) to make patterns easier to spot.

## Key variables

| Variable | Description |
|----------|-------------|
| `hba1c` | Hemoglobin A1c percentage |
| `hba1c_category` | Categorized HbA1c level |
| `carb_intake_g` | Daily carbohydrate intake (grams) |
| `diabetes_diagnosed` | Whether diabetes was diagnosed (1 = yes, 0 = no) |
| `age_group` | Age bracket for population grouping |
| `country` | Country of origin |

## How to use this

1. **Explore with Power BI**: Open `Diabetes.pbix` to interact with the dashboard. Good for quick pattern discovery and presenting findings.

2. **Work with the data**: Use `diabetes.csv` directly for:
   - Statistical analysis
   - Building predictive models
   - Creating your own visualizations

## Next steps

Some things worth exploring:
- Correlation between HbA1c and carb intake by age group
- How diabetes prevalence differs across countries
- Age as a factor in diabetes diagnosis
- Whether HbA1c thresholds are consistent across demographics

## Requirements

- Power BI Desktop (for `.pbix` files)
- Python + pandas (if working with the CSV directly)

---

Feel free to fork, adapt, or build on this analysis.
