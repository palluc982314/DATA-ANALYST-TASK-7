# Task 7: Basic Sales Summary using SQLite and Python

📌 Objective
The goal of this task is to use SQL within Python to extract basic sales metrics (like total quantity sold and total revenue), display the output using `print()` statements, and visualize the result with a simple bar chart using `matplotlib`.

🛠 Tools Used
- Python
- SQLite (via `sqlite3` module)
- Pandas
- Matplotlib
- Jupyter Notebook (Google Colab)

📂 Files Included
- `TASK_7_Sales_Summary_Completed.ipynb` – Jupyter Notebook with full implementation
- `README.md` – This file

 📊 Dataset
A small in-memory SQLite database (`sales`) was created with the following schema:

```sql
CREATE TABLE sales (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    product TEXT NOT NULL,
    quantity INTEGER NOT NULL,
    price REAL NOT NULL
);
