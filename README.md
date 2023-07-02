1.	Importing necessary libraries such as pandas, numpy, plotly, seaborn and matplotlib.
2.	Reading a csv file into a pandas DataFrame.
3.	Provide an overview of the data using .head() and .describe().
4.	Finding unique job titles.
5.	Calculating the average annual basic salary for each job title.
6.	Visualizing performance rating and annual basic salary distribution across different grades using boxplots.
7.	Mapping grades to numerical values for easier data manipulation.
8.	Mapping numerical grades to pay range midpoints.
9.	Calculating and adding a new column for Compa-Ratio (a measure of the comparison between an employee's salary and the midpoint of the salary range for their grade).
10.	Calculating and printing the median Compa-Ratio for each grade and each performance rating.
11.	Defining a function, calculate_bonus, that calculates the bonus rate based on performance rating and compo ratio.
12.	Creating a new column, merit_inc_rate, in the dataframe that applies the calculate_bonus function to every row.
13.	Converting the merit_inc_rate column to percentage.
14.	Creating a new column, pay_out, which calculates the bonus payout for each individual based on their merit_inc_rate and annual_basic_salary.
15.	Print the average payout for each numeric grade.
16.	Creating a boxplot to visualize the distribution of bonus payouts across grades.
17.	Calculating and printing the total sum of payouts.
18.	Calculate each grade's total payout and visualize it using a bar plot.
19.	Creating a histogram to visualize the distribution of payouts.
20.	Creating a QQ plot to check if the payout data is normally distributed.
21.	Creating a scatter plot to visualize the relationship between 'numeric_grade' and 'pay_out'.
22.	Calculating a scaling factor based on a target total payout of 50,000. This scaling factor is used to adjust the individual payouts such that the total payout is 50,000.
23.	Creating a grouped bar chart to compare the original payouts with the adjusted payouts for each grade.
24.	Calculating the difference between the original and adjusted payouts.
25.	Calculate the average difference for each grade.

