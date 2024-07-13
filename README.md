# FinanceTracker

Overview
Finance Tracker is a Python-based application designed to help you manage and track your financial transactions. You can record income and expenses, view transactions within a specified date range, and generate visual plots to analyze your financial data.

Features
Add new transactions (income or expense) with a date, amount, category, and description.
View transactions within a specified date range.
Summarize total income, total expenses, and net savings within a date range.
Visualize income and expenses over time using a plot.
Requirements
Python 3.x
pandas
matplotlib
Installation
Clone the repository or download the source code.
Ensure you have Python 3.x installed.
Install the required libraries by running:
sh
Copy code
pip install pandas matplotlib
Usage
Run the application by executing:

sh
Copy code
python finance_tracker.py
Follow the on-screen prompts to interact with the application:

Add a new transaction: Choose this option to record a new transaction. You will be prompted to enter the date, amount, category (Income or Expense), and a description.
View transactions and summary within a date range: Choose this option to view transactions between two dates. The application will display the transactions and provide a summary of total income, total expenses, and net savings. You will also have the option to plot the data.
Exit: Choose this option to exit the application.
Modules
get_date: Prompts the user to enter a date and validates the format.
get_amount: Prompts the user to enter a transaction amount and validates it.
get_category: Prompts the user to enter a category (Income or Expense) and validates it.
get_description: Prompts the user to enter a description for the transaction.
Classes
CSV: Handles CSV file operations, including initialization, adding entries, and fetching transactions within a date range.
initialize_csv: Initializes the CSV file if it does not exist.
add_entry: Adds a new transaction to the CSV file.
get_transactions: Retrieves transactions within a specified date range and provides a summary.
Plotting
plot_transactions: Plots the income and expenses over time based on the filtered transactions.
