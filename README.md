# Data-Analysis-on-CSV-Files

The objective of this task is to use Python and the Pandas library to perform a basic data analysis on a CSV file containing sales data. You are expected to use a notebook environment like Jupyter Notebook.

Key Steps & Deliverables:-

==> Load the CSV File: Use Pandas to read the provided CSV file into a DataFrame.

==> Analyze Data: Use the groupby() and sum() functions to derive basic data insights.

==> Visualize Data: Create a chart (specifically, a bar chart as suggested in the hints) to visualize the results of your analysis.

==> Deliverables: The final output should be the notebook file (.ipynb) containing your code and the generated charts.


The task is to perform data analysis on sales data using Python, specifically with the Pandas library. You are given a CSV file named sales_data.csv which contains detailed information about sales orders.


The task is to perform data analysis on sales data using Python, specifically with the Pandas library. You are given a CSV file named sales_data.csv which contains detailed information about sales orders.


The sales_data.csv file is a dataset of sales orders. Each row represents a single line item from an order. The columns provide specific details, including:

==> ORDERNUMBER: The unique identifier for the sales order.

==> SALES: The total sales amount for that specific line item.

==> PRODUCTLINE: The category or type of product sold (e.g., 'Motorcycles', 'Classic Cars').

==> ORDERDATE: The date the order was placed.

==> CUSTOMERNAME: The name of the customer who made the purchase.

And many other columns containing details like quantity, price, and customer location.

The core of the task is to use the PRODUCTLINE and SALES columns. You'll group the data by PRODUCTLINE to find the total SALES for each category.
