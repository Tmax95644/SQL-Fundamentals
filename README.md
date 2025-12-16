# SQL Fundamentals

This repository contains a collection of **foundational SQL projects** completed as part of structured practice and guided exercises. The goal is to demonstrate practical competence with core SQL concepts used in data analyst roles, including querying, aggregation, joins, and window functions.

The projects focus on **clear problem statements, readable SQL, and interpretable results**, rather than overly complex queries.

---

## Skills Demonstrated

* Writing clean `SELECT` queries
* Filtering with `WHERE`, `LIKE`, and `IN`
* Aggregations using `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
* Grouped analysis with `GROUP BY` and `HAVING`
* Sorting with `ORDER BY`
* Joining tables (`INNER JOIN`, `LEFT JOIN`, `CROSS JOIN`)
* Window functions (`RANK`, `LAG`, `NTILE`, running averages)
* Date and time functions (e.g. `strftime`)
* Creating readable outputs using aliases

---

## Projects Included

### 1. Cryptocurrency Exchange Ledger

**Dataset:** Transaction ledger for a fictional crypto exchange

**Key Questions Answered:**

* Total money in vs. money out
* Transaction volume by currency (Bitcoin dominance)
* Largest transactions (inbound vs outbound)
* Average transaction values by date and currency

**Concepts Used:**

* Aggregates (`SUM`, `AVG`, `COUNT`)
* Conditional filtering
* Grouping by date
* Rounding and column aliases

---

### 2. New York Restaurants Analysis

**Dataset:** Restaurant listings across NYC neighborhoods

**Key Questions Answered:**

* Distinct cuisines and neighborhoods
* High-rated restaurants (4+ stars)
* Price-based filtering for fine dining
* Keyword search using `LIKE`
* Top 10 restaurants by rating
* Rating classification using `CASE`

**Concepts Used:**

* `DISTINCT`
* Conditional logic with `CASE`
* Ranking with window functions
* Handling missing values

---

### 3. Twitch Gaming Data Analysis

**Dataset:** Stream viewing and chat activity data

**Key Questions Answered:**

* Most popular games and channels
* Viewer locations for League of Legends
* Viewing platforms (mobile vs site)
* Genre classification using `CASE`
* Viewership trends by hour of day
* Joining stream and chat data

**Concepts Used:**

* Multi-table joins
* Window functions
* Date/time extraction
* Grouped aggregations

---

### 4. Climate Change Analysis (Window Functions)

**Dataset:** Average annual temperatures by US state

**Key Questions Answered:**

* Running average temperature trends
* Year-over-year temperature change
* Coldest and warmest years on record
* Ranking and quartile/quintile analysis

**Concepts Used:**

* `LAG()` and running averages
* `RANK()` and `NTILE()`
* Partitioning by state
* Time-series comparisons

---

### 5. Lyft Trip Data (Joins Practice)

**Dataset:** Trips, riders, and cars

**Key Questions Answered:**

* Building trip logs with user data
* Linking trips to cars
* Identifying high-usage cars
* Aggregating trip costs

**Concepts Used:**

* `LEFT JOIN`, `INNER JOIN`, `UNION`
* Basic aggregation
* Understanding relational keys

---

## Tools

* SQL (SQLite-style syntax)
* Queries written and tested locally

---
