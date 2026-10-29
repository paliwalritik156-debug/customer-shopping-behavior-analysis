# Customer Shopping Behavior Analysis

## Project overview
A beginner-to-intermediate data analysis project using **Python, SQL, and Excel** to study customer purchases, product categories, spending, discounts, ratings, payment methods, and monthly trends.

**Important:** The included dataset is synthetic sample data created for this portfolio project. Do not present its results as real company findings.

## Tools
- Python: pandas, NumPy, Matplotlib
- SQL: SQLite-compatible queries
- Excel: KPI dashboard, summary tables, and charts

## Folder structure
- `data/customer_shopping_behavior.csv` — sample dataset (1,000 rows)
- `analysis.py` — cleaning, analysis, charts, and SQLite database creation
- `sql/analysis_queries.sql` — SQL business questions and queries
- `Customer_Shopping_Behavior_Dashboard.xlsx` — Excel dashboard and summary sheets
- `outputs/` — analysis output files and SQLite database

## How to run
1. Install Python 3.10+.
2. Open a terminal in the project folder.
3. Install dependencies: `pip install -r requirements.txt`
4. Run: `python analysis.py`
5. Open `Customer_Shopping_Behavior_Dashboard.xlsx` in Excel.
6. Open `sql/analysis_queries.sql` in SQLiteStudio, DB Browser for SQLite, or another SQLite client. The Python script creates `outputs/shopping_behavior.db` with a table named `shopping_behavior`.

## Business questions
1. What are total orders, unique customers, revenue, and average order value?
2. Which product categories generate the most revenue?
3. How does revenue change month by month?
4. Which products are purchased most often?
5. How do discounts relate to average order value and ratings?
6. Which payment methods are most popular?
7. How do customer subscription status and location relate to purchases?
8. Which categories receive the highest ratings?

## Suggested portfolio workflow
- Validate data types and duplicates in Python.
- Use SQL to answer business questions.
- Use Excel charts and KPIs to communicate the results.
- Add a short conclusion describing insights and limitations.
- Replace synthetic data with a sourced real dataset before making claims about actual customer behavior.


## Run the interactive dashboard

### Windows (easy method)
1. Install Python 3.10 or newer.
2. Double-click `RUN_DASHBOARD.bat`.
3. Wait for package installation. Streamlit will open the dashboard in your browser.
4. If it does not open automatically, copy the local address shown in the terminal (usually `http://localhost:8501`) into your browser.

### Run manually in VS Code
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m streamlit run app.py
```

The dashboard includes sidebar filters, KPIs, interactive charts, customer and product insights, a data explorer, CSV exports, and SQL-style grouped analyses. It can optionally load another CSV file. The included dataset is synthetic demonstration data.
