# A-Journey-Throught-Decades-of-Global-Suicides-Rates-

Our team consists of four members, with clear roles in data preparation, analysis, and visualization.

🎯 Project Overview

This data analysis project explores global suicide rates from 1985 to 2016, utilizing a comprehensive dataset from Kaggle. The study aims to provide crucial, data-driven insights into mental health challenges worldwide, helping public health policymakers and hospitals develop targeted prevention strategies.

We identified trends across different demographics and countries, analyzing the influence of factors like age, gender, and economic status (GDP and HDI) on suicide rates. The entire analysis and visualization dashboard were developed using the R programming language

📚 Data & Methodology
Data Source
The dataset, sourced from Kaggle, encompasses global suicide statistics from 1985 to 2016.

Key Variables Analyzed 





Demographic: Country, Year, Sex, Age Group, Generations.

Outcome: Suicides_no (Number of suicides), Suicides/100k pop (Rate per 100,000).

Economic Factors: GDP per capita, HDI for year.

Technical Stack
Language: R


Libraries: readxl, dplyr, writexl (for data cleaning).


Output: Interactive Shiny Dashboard for dynamic data analysis.

📊 Key Findings & Insights
The analysis identified several significant trends relevant for informing policy decisions and preventive measures.


Gender Disparity: Males consistently show a significantly higher suicide rate than females. In the United States, for example, males accounted for 78.9% of suicides, compared to 21.1% for females, indicating a stark disparity.




Age Vulnerability: The 75+ years age group and the 55–74 years age group showed the highest median age of suicides, highlighting the increased vulnerability of older populations.



Economic Correlation: Analysis of the United States showed a consistent upward trend in the Human Development Index (HDI) over the years, yet the USA was recorded as having the highest total suicide rates among the top countries visualized. This suggests that high economic development does not automatically translate to better mental health outcomes.



High Suicide Numbers: Globally, countries like Japan were recorded as having the most suicides, while the United States showed the highest median number of suicides and the widest variability among the top three countries analyzed.


🛠️ Data Preparation Steps
The data preparation was a critical step to ensure accuracy.


Load and Initial Exploration: Libraries were loaded (readxl, dplyr, writexl) and the initial data was explored using functions like head(), str(), and dim().



Cleaning: Missing values were handled (na.omit()) and duplicate rows were removed (distinct()).


Enhancement: A new quantitative column, Age_mean, was calculated using a custom function to determine the mean age within each qualitative age group, assuming the upper bound of the "75+ years" group is 100 years old.




Final Output: The refined dataset was saved as a Cleaned_Suicide_Data.xlsx file.

🚧 Limitations & Future Work
Temporal Range: The current data stops at 2016, excluding recent trends like the impact of the COVID-19 pandemic. Future work should focus on updating the data to include more current information.


Limited Variables: The analysis focused on core economic and demographic variables. Future analysis could be expanded to incorporate social support systems, mental health policies, and cultural aspects for a more comprehensive understanding.
