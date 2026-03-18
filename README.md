# -MMS-FT--practical-2-exam-all-sets
MySQL DDL &amp; DML practice — 10 real-world database sets (Bookstore, Hospital, University, Airline, Hotel, Library, Inventory, Food Delivery, Cinema, E-Learning) with table creation, sample data, and 25 queries each.
# MySQL Practical Exam — All 10 Sets

A complete MySQL solution for a practical exam covering 10 real-world database scenarios.  
Each set includes table creation, sample data insertion, and 25 queries.

---

## Databases Covered

| Set | Scenario |
|-----|----------|
| 1 | Online Bookstore |
| 2 | Hospital Management System |
| 3 | University Management System |
| 4 | Airline Reservation System |
| 5 | Hotel Management System |
| 6 | Library Management System |
| 7 | Inventory Management System |
| 8 | Online Food Delivery System |
| 9 | Cinema Ticket Booking System |
| 10 | E-Learning Platform |

---

## Structure

Each set contains:
- **DDL** — `CREATE TABLE` with constraints, primary keys, foreign keys, and checks
- **DML** — `INSERT INTO` with 5+ realistic records per table
- **Queries** — 25 SQL queries covering JOINs, aggregations, subqueries, filters, and more

---

## How to Run

1. Open **MySQL Workbench** (or any MySQL 8.0+ client)
2. Open the file `Practical_Exam_All10Sets.sql`
3. Run one SET at a time, or run the full file
4. Each set auto-creates its own database — no manual setup needed
```sql
-- Example: Run Set 1 only
USE Set1_Bookstore;
```

---

## Requirements

- MySQL 8.0 or higher
- MySQL Workbench (recommended) or any MySQL client

---

## Notes

- All dates are dynamic using `DATE_SUB(CURDATE(), INTERVAL N DAY)` — data stays fresh on any run date
- Some `HAVING` thresholds are lowered from the original exam values to return results with sample data — comments mark every such change
- Character set: `utf8mb4` with `utf8mb4_unicode_ci` for full Unicode support

---

## Topics Covered in Queries

- `WHERE`, `LIKE`, `BETWEEN`, `IN`
- `JOIN` (INNER, LEFT)
- `GROUP BY` + `HAVING`
- `Subqueries`
- `ORDER BY` + `LIMIT`
- `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
- `DATE_SUB`, `DATEDIFF`, `TIMESTAMPDIFF`
- `DATE_FORMAT` for monthly grouping
- Overlap detection using self-joins

---

## Author

**SDS**  
MySQL | Database Management | Practical Exam Prep
