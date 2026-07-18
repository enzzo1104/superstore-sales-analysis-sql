# Superstore Sales Analysis (SQL)
*[English](#english) | [Hrvatski](#hrvatski)*
---
## English

SQL-based analysis of retail sales data using SQLite and pandas, focused on demonstrating database query skills (SELECT, WHERE, GROUP BY, ORDER BY, HAVING). Companion project to [superstore-sales-analysis](https://github.com/enzzo1104/superstore-sales-analysis), repeating key analyses through SQL instead of pure pandas.

### Dataset

Superstore Sales Dataset — https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting — 9,800 orders, including order dates, regions, product categories, and sales values.

### Tools

- Python
- pandas — data loading and result handling
- sqlite3 — in-memory SQL database
- Google Colab — development environment

### SQL Concepts Used

- SELECT and FROM — basic querying
- WHERE — filtering rows before aggregation
- GROUP BY — aggregating sales by region and sub-category
- HAVING — filtering aggregated results
- ORDER BY — sorting results

### Key Findings

- Region — West leads in total sales (approx. 710K USD), followed by East (approx. 670K USD), Central (approx. 493K USD), and South (approx. 389K USD).
- Technology by Region — When filtering by Technology category specifically, East takes the lead (approx. 263K USD) ahead of West (approx. 247K USD) — a different pattern than the overall regional ranking.
- Sub-Categories Over 100K — Phones (approx. 328K USD) and Chairs (approx. 323K USD) are the top-selling sub-categories, with 10 out of 17 sub-categories exceeding 100K USD in sales.

### Notebook

Full analysis with SQL queries: [data_analysis_sql.ipynb](./data_analysis_sql.ipynb)

---

## Hrvatski

SQL analiza podataka o maloprodaji koristeći SQLite i pandas, s fokusom na demonstriranje vještina upita nad bazama podataka (SELECT, WHERE, GROUP BY, ORDER BY, HAVING). Prateći projekt uz [superstore-sales-analysis](https://github.com/enzzo1104/superstore-sales-analysis), koji ponavlja ključne analize kroz SQL umjesto čistog pandasa.

### Dataset

Superstore Sales Dataset — https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting — 9.800 narudžbi, uključujući datume narudžbi, regije, kategorije proizvoda i iznose prodaje.

### Alati

- Python
- pandas — učitavanje podataka i rad s rezultatima
- sqlite3 — in-memory SQL baza podataka
- Google Colab — razvojno okruženje

### Korišteni SQL koncepti

- SELECT i FROM — osnovni upiti
- WHERE — filtriranje redaka prije agregacije
- GROUP BY — agregacija prodaje po regiji i podkategoriji
- HAVING — filtriranje agregiranih rezultata
- ORDER BY — sortiranje rezultata

### Ključni nalazi

- Regija — Zapad ostvaruje najveću ukupnu prodaju (oko 710K USD), slijede Istok (oko 670K USD), Centar (oko 493K USD) i Jug (oko 389K USD).
- Tehnologija po regiji — Kad se filtrira samo kategorija Technology, Istok preuzima vodstvo (oko 263K USD) ispred Zapada (oko 247K USD) — drugačiji obrazac nego u ukupnom rangiranju regija.
- Podkategorije preko 100K — Telefoni (oko 328K USD) i Stolice (oko 323K USD) su najprodavanije podkategorije, s 10 od ukupno 17 podkategorija preko 100K USD u prodaji.

### Notebook

Cijela analiza sa SQL upitima: [data_analysis_sql.ipynb](./data_analysis_sql.ipynb)
