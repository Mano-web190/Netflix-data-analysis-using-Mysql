** Netflix Data Analysis Using MySQL**

## 📁 Project Overview

This project showcases** **SQL-based business insights**** extracted from a fictionalized Netflix dataset. It contains **15 business-focused queries** written in **MySQL**, helping understand user preferences, content trends, and platform offerings. The goal is to demonstrate **data analysis proficiency using SQL** on real-world media platform scenarios.

---

## 🛠️ Tools & Technologies

* **MySQL** (Structured Query Language)
* SQL Functions: `JOIN`, `GROUP BY`, `RANK()`, `SUBSTRING_INDEX`, `STR_TO_DATE`, `FIND_IN_SET`, `CASE`, etc.
* Platform: Any SQL-compatible IDE (e.g., MySQL Workbench, DBeaver)

---

## 📌 Dataset Schema

Table: `netflix_tables`
Columns:

* `show_id` – Unique identifier for content
* `type` – Movie or TV Show
* `title` – Name of the show
* `director` – Director(s)
* `casts` – Actors featured
* `country` – Country of origin
* `date_added` – Date Netflix added it
* `release_year` – Year of release
* `rating` – Age rating (e.g., TV-MA, PG-13)
* `duration` – Runtime or number of seasons
* `listed_in` – Genre(s)
* `description` – Summary

---

## 🔍 Business Problems Solved

1. **Count of Movies vs TV Shows**
2. **Most Common Rating per Content Type**
3. **Movies Released in a Specific Year (e.g., 2020)**
4. **Top 5 Countries with Most Content**
5. **Longest Movie on Netflix**
6. **Content Added in the Last 5 Years**
7. **Content Directed by Rajiv Chilaka**
8. **TV Shows with More than 5 Seasons**
9. **Content Count per Genre**
10. **Top 5 Years with Highest Avg Content Release by India**
11. **List of Documentaries**
12. **Content Without a Director**
13. **Movies Featuring Salman Khan in Last 10 Years**
14. **Top 10 Indian Actors by Appearances**
15. **Content Categorization Based on 'Violence' and 'Kill' in Description**

---

## 📂 File Structure

* `Mysql query - Netflix.sql` – All 15 SQL queries
* `README.md` – Project overview and documentation

---

## ✅ How to Use

1. Load the `netflix_tables` schema into MySQL.
2. Run the queries sequentially from the `.sql` file.
3. Modify the logic (like actor name, year, etc.) as needed for custom analysis.

---

## 📈 Skills Demonstrated

* Data Cleaning (handling NULLs, splitting fields)
* Aggregation & Ranking
* Window Functions
* Text-based Filtering
* Genre and Actor Analysis
* Temporal Filtering

