3. Laboratory and Greenhouse Databases - Database Design and Stored Procedures - SQL

MySQL exercises focused on relational database design and basic SQL programming, created to practice structuring relational databases and applying SQL concepts to scientific datasets.

## Overview

- **Dataset:** two databases built from scratch — a **laboratory database** (experiments, employees, tools, results) and a **greenhouse database** (plants, gardeners, greenhouses) — plus stored procedures on a protein-structure database
- **Task:** design the tables, link them with keys, and write reusable queries
- **Focus:** clean relational design, with data integrity enforced by constraints

## Databases at a glance

| Database | Tables | Highlights |
|---|---|---|
| Laboratory | 7 (incl. 3 linking tables) | Experiments linked to employees, tools and results (many-to-many) |
| Greenhouse | 5 (incl. 2 linking tables) | Gardeners and plants linked to greenhouses (many-to-many) |
| Protein structures | queried only | 7 stored procedures, incl. subqueries |

## Approach

1. **Stored procedures:** wrote reusable procedures to query organisms, proteins and structures, using filters and subqueries.\
   → *Stored procedures, subqueries and filtering*
2. **Database design:** created the laboratory and greenhouse databases, with primary keys, foreign keys and linking tables for many-to-many relationships.\
   → *Relational database design, primary and foreign keys, many-to-many relationships*
3. **Data integrity:** added `CHECK`, `UNIQUE`, `NOT NULL` and `DEFAULT` constraints (e.g. e-mail format, positive salaries, allowed weekdays).\
   → *Data validation with constraints*

## Tech stack

SQL · MySQL

## Files

- `3. SQL-Stored_Procedures_and_Database-Creation.sql` — SQL code only
