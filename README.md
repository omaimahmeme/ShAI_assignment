Employee Salaries Dataset

Overview:
The dataset contains information about employee salaries, including details such as employee names, job titles, base pay, overtime pay, benefits, and total pay. The analysis aimed to explore the distribution of salaries, identify any correlations, handle missing values, and compare average salaries across different groups.

Data Cleaning:
The 'Id' and 'Year' columns were converted to object types, considering their categorical nature.
Columns 'Notes' and 'Status,' with no variation and missing values, were dropped to simplify the dataset.

Handling Missing Values:
Missing values in numerical columns ('BasePay', 'OvertimePay', 'OtherPay', 'Benefits') were imputed with the mean, assuming they were missing at random.
Columns with a high percentage of missing values ('Notes' and 'Status') were dropped or filled with placeholder values, depending on their relevance.

Distribution of Salaries:
A histogram was created to visualize the distribution of salaries ('TotalPay'). The distribution appeared right-skewed, with a concentration of salaries around a certain range.

Correlation Analysis:
The correlation between 'TotalPay' and 'BasePay' was explored using scatter plots. A positive correlation was observed, indicating that as base pay increases, total pay also tends to increase.
Group Analysis:

The dataset was grouped by job title, and summary statistics for 'TotalPay' were calculated (mean, median, min, max, count). This allowed for the comparison of average salaries across different job titles.
