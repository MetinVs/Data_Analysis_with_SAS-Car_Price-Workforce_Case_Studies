# Data Analysis with SAS – Car Price & Workforce Case Studies

This project showcases exploratory data analysis, visualization, and statistical modeling performed using **SAS 9.4**. The primary dataset covers car listings from CarDekho, while additional exercises were performed using simulated fitness and workforce data.

---

## Datasets Used

1. **Car Dataset** (CarDekho)
   - Features: Car brand, year, fuel type, transmission, owner count, horsepower, selling price
   - Size: ~300 records
   - Purpose: Perform statistical summaries, visualizations, and hypothesis testing on car market data

2. **Body Fat Dataset** (Simulated)
   - Features: Gender, fat %, age, BMI
   - Purpose: Compare distributions across gender using parametric and non-parametric tests

3. **Workforce (Job Metrics) Dataset** (Simulated)
   - Features: Department, number of employees, average age, yearly budget
   - Purpose: Run ANOVA, correlation, and regression analyses

---

## Key Analyses Performed

- **Descriptive Statistics**:
  - `PROC MEANS`, `PROC UNIVARIATE`, `PROC FREQ`
  - Summary tables with mean, std dev, CI, and skewness

- **Visualization**:
  - Histograms, bar charts, boxplots, SGPLOT
  - Scatterplots with regression lines

- **Hypothesis Testing**:
  - `PROC TTEST`, `PROC NPAR1WAY` (Wilcoxon)
  - ANOVA with multiple comparisons (Tukey, Bonferroni, Dunnett)

- **Data Transformation**:
  - Created new variables (`car_age`, `bmi`)
  - Applied `PROC FORMAT` to clean categorical features

- **Regression Analysis**:
  - Simple and multiple regression models
  - Confidence & prediction intervals

---

## Files Included

- `SAS-Code.docx`: Cleaned full code set
- `SAS-MMV.pdf`: Report version of the project
- `Results.html`: ODS output (all graphs and tables)

---

## Tools Used
- SAS 9.4
- SAS Studio / Enterprise Guide
- ODS HTML output

---

## Outcomes
This project demonstrates the full cycle of SAS-based data analysis: importing, cleaning, labeling, exploring, testing, modeling, and reporting results. While inspired by coursework, the exercises were independently expanded and refined for portfolio purposes.
