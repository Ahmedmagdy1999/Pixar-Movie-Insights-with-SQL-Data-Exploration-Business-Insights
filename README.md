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
