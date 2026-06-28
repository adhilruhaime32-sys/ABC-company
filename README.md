# README: ABC Company Employee Dataset Analysis

This report provides a comprehensive analysis of the ABC Company employee dataset, covering preprocessing, distribution analysis, salary expenditure insights, and age-salary correlation.

## 1. Preprocessing Steps

*   **Data Loading:** The initial dataset was loaded from an Excel file named `Copy of ABC Company.xlsx` into a pandas DataFrame.
*   **Feature Engineering:** The 'Height' column was replaced with randomly generated integer values between 150 and 180 (inclusive).
*   **Handling Missing Values:** Missing values in the 'Salary' column were filled with 0 to ensure accurate expenditure calculations.
*   **Categorization:** Employees were categorized into 'Age Group' bins (18-24, 25-34, 35-44, 45-54, 55-64, 65+) for easier analysis of age distribution.

## 2. Analysis Tasks and Key Insights

### 2.1 Employee Distribution by Team and Position

*   **Team Distribution:** The company's employee distribution across teams shows some variation. 'New Orleans Pelicans' has the highest number of employees (19), while 'Orlando Magic' and 'Minnesota Timberwolves' have the lowest (14 each). This indicates a slightly uneven distribution, potentially influenced by team-specific requirements.
*   **Position Distribution:** 'SG' (Shooting Guard) and 'PF' (Power Forward) are the most common positions with 102 and 100 employees respectively. 'C' (Center) is the least common with 79 employees, suggesting a focused need for specific roles within the company structure.

### 2.2 Predominant Age Group

*   The predominant age group among employees is **'25-34'**, accounting for 272 out of 458 employees. The '18-24' age group is also significant with 154 employees. This indicates a relatively young workforce, with a strong concentration in their mid-twenties to early thirties. Older age brackets ('45-54', '55-64', '65+') have zero employees, suggesting a young average workforce.

### 2.3 Highest Salary Expenditure

*   **Team with Highest Salary Expenditure:** The 'Cleveland Cavaliers' team has the highest total salary expenditure, amounting to $106,988,689.00. This could be due to a larger team size, higher-paid individuals, or a combination of both.
*   **Position with Highest Salary Expenditure:** The 'C' (Center) position has the highest total salary expenditure, totaling $466,377,332.00. Despite being the least common position by count, individuals in this role command the highest overall average salary.

### 2.4 Age and Salary Correlation

*   The correlation coefficient between 'Age' and 'Salary' is approximately **0.21**. This indicates a **weak positive correlation**. While there's a slight tendency for salary to increase with age, it's not a strong relationship. This suggests that other factors such as position, performance, or team likely play a more significant role in determining an employee's salary within ABC Company. The scatter plot visualization supports this, showing a wide spread of salaries across different age groups.

## 3. Graphical Representations

The analysis is supported by several visualizations:

*   **Scatter Plot:** Illustrates the correlation between 'Age' and 'Salary'.
*   **Bar Plots:** Show the distribution of employees across teams, by position, by age group, and highlight the teams and positions with the highest salary expenditures.
