# QuantLake Internship Progress Log

## Week 1

---

###  Day 1 - Python Basics
-  Task Done: Yes
-  Environment: Google Colab / VS Code + Git
-  Learned:
  - Data types: `int`, `float`, `str`, `bool`
  - Lists, tuples, dictionaries
  - Conditional statements (`if-elif-else`)
  - Looping using `for` and `while`
-  Reflection:
  - Brushed up on Python control flow and basic data structures
  - Set up GitHub repo and pushed first notebook

---

###  Day 2 - Python Fundamentals
-  Task Done: Yes
-  Learned:
  - List comprehension and set operations
  - Writing reusable functions (e.g., factorial, prime check)
  - Exception handling using `try-except-finally`
  - Standard modules: `math`, `random`, `datetime`
  - Practiced mini coding problems like FizzBuzz and string reversal
-  Blockers:
  - Confusion on function scope and recursion initially
-   Solution:
  - Used print-based debugging and small test cases
-  Reflection:
  - Gained confidence in writing clean, functional Python code

---

###  Day 3 - Pandas Introduction
-  Task Done: Yes
-  Dataset Used: `Iris` dataset from `sklearn`
-  Learned:
  - Series and DataFrames
  - Data inspection methods: `head()`, `info()`, `describe()`, `isnull().sum()`
  - Indexing using `loc` and `iloc`
  - Column operations: `mean()`, `value_counts()`, `sort_values()`, `drop()`
-  Reflection:
  - Strong first experience with real-world data structures in Pandas

---

###  Day 4 - Pandas Data Manipulation with Netflix Dataset
-  Task Done: Yes
-  Dataset Used: `netflix_titles.csv`
-  Learned:
  - Row filtering based on `country`, `type`, and `release_year`
  - Sorting dataframes using single and multiple columns
  - Handling missing values using `fillna()`
  - Aggregating data using `groupby()` with multiple columns
  - DataFrame merging using `pd.merge()` (demo with platform and content stats)
-  Blockers:
  - Initial KeyError while trying to use incorrect column names like `'Sales'`
-  Solution:
  - Used `df.columns` to inspect real structure and update all operations accordingly
-  Reflection:
  - Learned how to adapt standard data manipulation tasks across datasets


### Day 7 - SQL Basics & SELECT Queries
-  Task Done: Yes
-  DB Used: In-memory SQLite
-  Queries Practiced:
  1. SELECT * FROM customers;
  2. SELECT order_id, region FROM orders;
  3. WHERE country = 'USA' and amount > 500
  4. ORDER BY amount DESC LIMIT 3
  5. GROUP BY region and AVG(sales)
-  Reflection:
  - Learned filtering, sorting, and aggregation in SQL
  - Practiced on small dummy dataset using `sqlite3` and Pandas



### Day 8 - SQL & Data Integration
-  Task Done: Yes
-  Tools: SQLite + Pandas + sqlite3
-  SQL Used:
  - GROUP BY + Aggregation (AVG, COUNT)
  - WHERE with subquery
  - UPDATE and DELETE operations
-  Integration:
  - Used sqlite3 in Python to query data into Pandas
  - Performed SQL-style JOIN using pd.merge()
-  Insights:
  - SQL is easier for filtering and joining large datasets
  - Pandas is better for exploring, transforming, and visualizing
-  Favorite:
  - I liked using `pd.merge()` to simulate SQL JOIN inside Python seamlessly

  ### Day 9 - Advanced SQL Analytics & Business Queries
-  Task Done: Yes
-  New Skills:
  - Multi-table JOINs and CTEs
  - Window functions: RANK(), SUM() OVER()
  - Identifying business insights from revenue & trend data
-  Business Insight:
  - Found Alice and Bob were top spenders
  - Noted declining revenue trend in some Furniture products
-  Most Challenging:
  - Writing nested window functions and aligning product-wise monthly revenue
