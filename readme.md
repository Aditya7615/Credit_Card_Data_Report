⚡ Quickstart Steps
1. Load Data into MySQL
Import these CSV files:

credit_card.csv

customer.csv

cc_add.csv

cust_add.csv

Use MySQL LOAD DATA LOCAL INFILE command or your favorite database tool.

Ensure you create the tables: cc_detail, customer_detail.

2. Connect Power BI to MySQL
Open Power BI Desktop.

Get Data → MySQL Database → Enter your connection details.

Import or DirectQuery the tables cc_detail and customer_detail.

3. Build or Open the Dashboard
Open the prepared Power BI report.

Make sure table relationships are set (e.g., Customer ID linking customer and transactions).

Refresh the dashboard to load the latest data from MySQL.

🎯 Dashboard Features
Quarterly Revenue and Transaction Trends

Revenue by Expenditure, Card Type, Education, Salary, State, and Gender

Dynamic updates when MySQL data is refreshed!

🔗 Technologies Used
Power BI

MySQL Database

SQL for data loading

CSV Data Sources

🛠️ Requirements
MySQL Server with local_infile enabled

Power BI Desktop installed

Access to the CSV files and database credentials

📋 Notes
New customer and transaction records (cust_add.csv, cc_add.csv) can be loaded anytime.

After updating data, just Refresh the Power BI report to view changes.

👨‍💻 Author
Name: Aditya Goyal

Contact: https://www.linkedin.com/in/adityagoyal7615/
