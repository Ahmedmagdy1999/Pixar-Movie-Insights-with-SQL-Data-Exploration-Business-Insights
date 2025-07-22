# Pixar Movie Data Analysis with SQL Server 🎬

## 📊 Overview
This project showcases advanced SQL analysis on a Pixar movie dataset. The goal is to answer business questions using SQL queries and structured data from Excel.

---

## 📁 Dataset Description
The dataset consists of multiple Excel sheets, including:
- `pixar_films` – movie metadata (title, release date, runtime, rating, plot)
- `box_office` – budget and gross performance
- `awards` – nominations and wins
- `genre` – main and subgenres
- `reviews` – Rotten Tomatoes and IMDb scores
- `crew` – director and main cast
- `franchise` – film series grouping

---

## 🔍 Business Questions Answered

### ✅ Task 1: Financial Performance
```sql
-- List all films with title, release year, budget, worldwide gross, and ROI%
-- Exclude films with zero or missing budgets
-- Order by ROI in descending order

✅ Task 2: Award Analysis

-- List all films that won at least one Academy Award
-- Include total nominations and win percentage
-- Order by win percentage descending
✅ Task 3: Genre Profitability

-- Show top 5 profitable subgenres (appearing in at least 3 films)
-- Include average gross and count of films
✅ Task 4: Director Impact Study

-- Directors with 2+ films
-- Include average IMDb, Rotten Tomatoes, and box office performance
✅ Task 5: Franchise Comparison

-- Analyze franchises: Toy Story, Cars, Finding Nemo/Dory
-- Include total films, total gross, and average runtime
✅ Task 6: Budget Category Analysis
-- Group films by budget category: Low, Medium, High
-- Show average Metacritic score, gross, and count per category
⚙️ Tools Used
SQL Server (Microsoft SQL Server Management Studio)

Excel (Data Preparation)

GitHub (Project Documentation & Version Control)

📌 Skills Demonstrated
Complex SQL Queries (JOIN, GROUP BY, CASE, CAST, ROUND)

Data Cleaning & Import from Excel

Business-Oriented Data Analysis

Result Interpretation & Communication

📸 Screenshots
You can find query screenshots and result snippets in the /screenshots folder.

📎 Author
Ahmed Magdy Sayed Yahia
LinkedIn Profile
GitHub: github.com/Ahmedmagdy1999

💼 Use Case
This project simulates real business reporting cases and would be a great fit in:

Internships

Junior Data Analyst Portfolios

BI Roles using SQL & Excel
