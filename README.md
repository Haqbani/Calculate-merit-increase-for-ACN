## In below, you can find the recorded steps explanation for the code operation

📚 Importing necessary libraries such as pandas, numpy, Plotly, seaborn and matplotlib.

📂 Reading a CSV file into a pandas DataFrame.

🔎 Provide an overview of the data using .head() and .describe().

🔍 Finding unique job titles.

💰 Calculating the average annual basic salary for each job title.

📊 Visualizing performance rating and annual basic salary distribution across different grades using boxplots.

↗️ Mapping grades to numerical values for easier data manipulation.

📍 Mapping numerical grades to pay range midpoints.

📈 Calculating and adding a new column for Compa-Ratio (a measure of the comparison between an employee's salary and the midpoint of the salary range for their grade).

📝 Calculating and printing the median Compa-Ratio for each grade and each performance rating.

🧮 Defining a function, calculate_bonus, that calculates the bonus rate based on performance rating and compo ratio.

🗂 Creating a new column, merit_inc_rate, in the data frame that applies the calculate_bonus function to every row.

🔄 Converting the merit_inc_rate column to percentage.

💼 Creating a new column, pay_out, which calculates the bonus payout for each individual based on their merit_inc_rate and annual_basic_salary.

💹 Print the average payout for each numeric grade.

📦 Creating a boxplot to visualize the distribution of bonus payouts across grades.

🧾 Calculating and printing the total sum of payouts.

💸 Calculate each grade's total payout and visualize it using a bar plot.

❓ If you're facing any issues or need help with the continuation of the code, please let me know. Please be as specific as possible about the tasks you want to perform or your problems, and I'll do my best to help you.

📌 Remember, for code meant to be run on Kaggle, ensure you run it in a Kaggle notebook to ensure it works as expected. Kaggle has specific file paths and certain libraries pre-installed, so running the code in a different environment might lead to issues.

📉 Creating a histogram to visualize the distribution of payouts.

🔬 Creating a QQ plot to check if the payout data is usually distributed.

📝 Creating a scatter plot to visualize the relationship between 'numeric_grade' and 'pay_out.'

📐 Calculate a scaling factor based on a target total payout of 50,000. This scaling factor is used to adjust the individual payouts such that the total payout is 50,000.

📊 Creating a grouped bar chart to compare the original payouts with the adjusted payouts for each grade.

➖ Calculating the difference between the original and adjusted payouts.

🧮 Calculate the average difference for each grade.
