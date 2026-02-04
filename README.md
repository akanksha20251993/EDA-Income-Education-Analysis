EDA-Income-Education-Analysis
Exploratory Data Analysis of income outcomes based on gender, school type, and major using R.

Project Overview
This project performs exploratory data analysis (EDA) to understand how income five years after graduation varies based on gender, school type, age, and academic major. The goal is to identify income patterns and provide data-driven insights that support education and career decision-making.

Dataset Description
The dataset contains hypothetical graduate information, including:
- Gender
- Age at graduation
- School type (public vs. private)
- Business major
- Income five years after graduation

Tools & Technologies
- R
- dplyr
- ggplot2

Analysis Performed
- Cleaned raw data by removing currency symbols and converting income to numeric format
- Removed unnecessary columns generated from Excel formatting
- Performed univariate analysis on income distribution
- Compared income across gender and school type using boxplots
- Interpreted findings in clear, business-focused language

Key Visualizations
Income Distribution
![Income Distribution](plots/income_histogram.png)

Income by Gender
![Income by Gender](plots/income_by_gender.png)

Income by School Type
![Income by School Type](plots/income_by_school_type.png)

Key Insights
- Income distribution is right-skewed, indicating a small group of high earners.
- Male and female income distributions largely overlap, suggesting no strong gender-based income difference in this dataset.
- Income ranges across school types show significant overlap, indicating that school type alone does not guarantee higher income.


Conclusion
This project demonstrates practical skills in data cleaning, visualization, and exploratory analysis using R. The findings highlight the importance of using data-driven insights rather than assumptions when evaluating income outcomes.
