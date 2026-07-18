<div align="center">

# 🐬 MySQL — From Zero to Query Master

### A hands-on, example-driven guide to writing real-world SQL in MySQL

[![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://dev.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📖 About This Repository

This is a **structured, beginner-to-advanced MySQL reference** built to pair with the video course. Every guide is written as a standalone lesson with clear explanations, copy-paste-ready SQL, and worked examples against a single, consistent sample database — so concepts build naturally from one part to the next.

Whether you're preparing for an interview, leveling up at work, or just starting out, work through the parts in order or jump straight to the topic you need.

## 🚀 Getting Started

1. **Set up the sample database** — start with [Part 0: Sample Database](docs/00-sample-database.md) and run the schema + seed data in your MySQL instance.
2. **Practice** — every query in these docs runs against the sample database, so you can experiment as you learn.

```bash
# Clone the repo
git clone https://github.com/AbulQasim123/Mysql.git
cd Mysql

# Load the sample database into MySQL, then start with docs/00-sample-database.md
```

## 📚 Course Contents

| # | Topic | Guide |
|---|-------|-------|
| 0 | Sample Database (schema & seed data) | [Sample Database](docs/00-sample-database.md) |
| 1 | Filtering Data (`WHERE`, operators, patterns) | [Filtering Data](docs/01-filtering-data.md) |
| 2 | Aggregate Functions, `GROUP BY` & `HAVING` | [Aggregate Functions & GROUP BY](docs/02-aggregate-functions-and-group-by.md) |
| 3 | JOINs (INNER, LEFT, RIGHT, SELF) | [Joins](docs/03-joins.md) |
| 4 | Subqueries | [Subqueries](docs/04-subqueries.md) |
| 5 | Window Functions | [Window Functions](docs/05-window-functions.md) |
| 6 | Common Table Expressions (CTEs) | [Common Table Expressions](docs/06-common-table-expressions.md) |
| 7 | String, Date & `CASE` Functions | [String, Date & CASE Functions](docs/07-string-date-and-case-functions.md) |
| 8 | Views (virtual tables) | [Views](docs/08-views.md) |
| 9 | Stored Procedures | [Stored Procedures](docs/09-stored-procedures.md) |
| 10 | Triggers (automatic `INSERT`/`UPDATE`/`DELETE` actions) | [Triggers](docs/10-triggers.md) |
| 11 | `UNION` & `UNION ALL` (stacking result sets) | [UNION & UNION ALL](docs/11-union-and-union-all.md) |
| 12 | Recursive CTEs (hierarchies & sequence generation) | [Recursive CTE](docs/12-recursive-cte.md) |


## 🗂️ Repository Structure

```
mysql/
├── docs/                 # Lesson guides (start with 00, follow in order)
│   ├── 00-sample-database.md
│   ├── 01-filtering-data.md
│   ├── 02-aggregate-functions-and-group-by.md
│   ├── 03-joins.md
│   ├── 04-subqueries.md
│   ├── 05-window-functions.md
│   ├── 06-common-table-expressions.md
│   ├── 07-string-date-and-case-functions.md
│   ├── 08-views.md
│   ├── 09-stored-procedures.md
│   ├── 10-triggers.md
│   ├── 11-union-and-union-all.md
│   └── 12-recursive-cte.md
├── assets/               # Diagrams & images
│   └── joins.png
├── LICENSE
└── README.md
```

## 🎯 Who This Is For

- **Beginners** learning SQL for the first time
- **Developers & analysts** brushing up on intermediate/advanced querying
- **Interview candidates** revising joins, subqueries, window functions, and CTEs
