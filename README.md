💸 Smart Expense Tracker

A simple and interactive Expense Tracker Web Application built using Python, Streamlit, and Pandas.

The application helps users record, manage, filter, and analyze their daily expenses. It also provides spending insights and a monthly budget tracker.

🚀 Features

- ➕ Add Expense
  
  - Add date, amount, category, and description.
  - Supported categories:
    - Food
    - Travel
    - Shopping
    - Bills
    - Health
    - Other

- ✏️ Update / Delete Expenses
  
  - Select an existing expense.
  - Edit expense details.
  - Delete unwanted records.

- 🔍 Filter Expenses
  
  - Filter expenses by date range.
  - Filter expenses by category.

- 🧠 Smart Insights
  
  - Total spending by category.
  - Highest spending category.
  - Average daily spending.
  - Spending during the last 7 days.
  - Spending during the last 15 days.
  - Spending alerts.
  - Category-wise bar chart.
  - Monthly spending trend.

- 🎯 Budget Tracker
  
  - Set a monthly budget.
  - View current month's spending.
  - View remaining budget.

- 📂 Upload / Download
  
  - Upload expenses using a CSV file.
  - Download expense data as CSV.

🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- CSV
- DateTime

📁 Project Structure

Smart-Expense-Tracker/
│
├── expense.py
├── expenses.csv
└── README.md

«"expenses.csv" is automatically used by the application to store expense data.»

⚙️ Installation

1. Clone the repository

git clone YOUR_REPOSITORY_URL

2. Open the project folder

cd Smart-Expense-Tracker

3. Install required libraries

pip install streamlit pandas

4. Run the application

streamlit run expense.py

The application will open in your browser.

📊 How It Works

The application stores expense records with four main fields:

Field| Description
Date| Date of the expense
Amount| Amount spent
Category| Expense category
Description| Additional details

The application saves the data in "expenses.csv" and loads it when the application starts.

🧠 Smart Insights

The Insights section analyzes the stored expenses and displays:

- Top spending category
- Average daily spending
- Last 7 days' spending
- Last 15 days' spending
- Category spending chart
- Monthly spending trend
- Spending alerts

🎯 Budget Tracking

Users can enter a monthly budget and the application calculates:

Remaining Budget = Monthly Budget - Amount Spent

The application also provides alerts when spending becomes high.

📂 CSV Format

A compatible CSV file should contain the following columns:

Date,Amount,Category,Description

Example:

2026-10-01,500,Food,Lunch
2026-10-02,1200,Shopping,Clothes
2026-10-03,300,Travel,Bus

🔮 Future Improvements

Possible improvements include:

- User login and authentication
- Database integration
- Pie charts and advanced visualizations
- Export reports as PDF
- Automatic monthly reports
- Expense prediction using Machine Learning
- Mobile-friendly interface
- Cloud deployment

👩‍💻 Author

Preeti Kumari

---

⭐ If you find this project useful, consider giving the repository a star!
