# IBM HR Analytics: Employee Attrition & Performance Modeling

## Project Overview
An exploratory data analysis and predictive modeling pipeline to investigate factors influencing employee turnover (attrition) within an organization. The goal is to identify key workforce retention drivers—such as overtime, monthly income, department dynamics, and job satisfaction—to support strategic human resources decision-making.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance (Kaggle)
- **Dataset Link:** [https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset]

## Analysis & Methodology
1. **Data Preprocessing & Cleaning:**
   - Evaluated dataset integrity across 1,470 employee records and 35 structural/categorical features with zero missing values.
   - Converted binary categorical fields (`Attrition`, `OverTime`) into numerical indicators (`1` and `0`) to streamline statistical and correlation evaluations.
   - Cast text-based categorical attributes into appropriate data types for streamlined grouped aggregations.
2. **Exploratory Data Analysis (EDA):**
   - Conducted multivariate visualizations examining attrition count distributions across departments and business travel frequencies.
   - Analyzed the direct impact of working overtime on employee attrition probability.
   - Evaluated monthly income distributions and tenure trends (`YearsAtCompany`, `TotalWorkingYears`) relative to employee retention.
   - Generated a comprehensive correlation matrix heatmap to isolate multi-collinear numerical features.
3. **Statistical Visualization:**
   - Utilized Seaborn and Matplotlib to map out categorical counts, density distributions, and income boxplots.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn# IBM-HR-Analytics-Employee-Attrition-Performance-Modeling
