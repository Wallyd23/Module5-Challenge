# Module5-Challenge
This Python script is designed to analyze data from a preclinical study investigating the efficacy of various drug regimens on tumor growth in mice. The study involves tracking tumor volume and other relevant metrics over time for mice treated with different drugs. The script performs data cleaning, statistical analysis, and data visualization to derive insights from the study data.

Dependencies:

pandas: Used for data manipulation and analysis.
matplotlib: Employed for creating visualizations.
scipy: Utilized for statistical analysis.

Functions:

1. Data Import and Integration:

Imports the mouse metadata and study results CSV files using pandas.
Merges the two datasets based on a common identifier (Mouse ID) to create a unified DataFrame for analysis.

2. Data Cleaning:

Checks for and removes any duplicate entries in the combined DataFrame to ensure data integrity.
Conducts basic data validation checks to identify any anomalies or inconsistencies in the data.

3. Summary Statistics:
Calculates summary statistics for tumor volume, including mean, median, variance, standard deviation, and standard error of the mean, for each drug regimen used in the study.
Presents the summary statistics in a tabular format for easy interpretation.

4. Data Visualization:

Generates various visualizations to aid in data exploration and presentation.
Includes bar plots to visualize the distribution of observations across different drug regimens.
Utilizes pie charts to illustrate the gender distribution of mice in the study.
Produces box plots to visualize the distribution of tumor volume for each treatment group.
Creates line plots to display tumor volume over time for individual mice within specific treatment groups.
Generates scatter plots to explore the relationship between mouse weight and average tumor volume.

5. Statistical Analysis:

Calculates the correlation coefficient between mouse weight and average tumor volume for the Capomulin treatment group.
Performs linear regression analysis to model the relationship between mouse weight and tumor volume.