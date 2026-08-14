# BTPR3203 Python for Data Science – Case Study

## Smart Manufacturing Resource Efficiency Dataset Analysis

This project analyses the Smart Manufacturing Resource Efficiency Dataset to investigate sustainable manufacturing performance through energy consumption, recycled material usage, production output, and defect rate.

The dataset contains 10,000 manufacturing records covering the period from 1 May 2025 to 5 June 2025.

## Research Questions

### RQ1
Does the Smart Manufacturing Resource Efficiency Dataset contain any data quality issues, including incorrect data types, missing values, duplicate records, or invalid numerical values, for the period from 1 May to 5 June 2025?

### RQ2
What is the strength and direction of the relationship between energy consumption (kWh) and production output (units) in the dataset from 1 May to 5 June 2025?

### RQ3
How do the six material categories differ in recycled material usage, production output, and defect rate in the dataset from 1 May to 5 June 2025?

## Methods

The analysis was conducted using Python with the following libraries:

- pandas
- numpy
- matplotlib

The analysis includes:

1. Data structure and data quality assessment
2. Timestamp transformation
3. Missing value and duplicate checking
4. Numerical consistency checking
5. Pearson correlation analysis
6. Grouped descriptive statistics
7. Data visualisation

## Main Findings

### RQ1 – Data Quality

No missing values, duplicate records, or invalid numerical values were identified. The Timestamp variable was successfully converted to datetime format.

### RQ2 – Energy Consumption and Production Output

The Pearson correlation coefficient was **-0.002**, indicating an extremely weak negative linear relationship between energy consumption and production output.

### RQ3 – Material Category Comparison

The Recycled Material category recorded the highest average recycled material usage at **25.06%**. Production output and defect rate showed relatively small differences across the six material categories.

## Repository Contents

- `Smart_Manufacturing_Analysis.ipynb` – Executed Python analysis notebook
- `smart_manufacturing_dataset.csv` – Dataset used for the analysis
- `.png` files – Generated visualisations

## Dataset Source
Ziya. (2025). Smart manufacturing resource efficiency dataset. In Kaggle.com. 
