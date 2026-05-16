# SQL-The Saviour

| If question says                | Think                     |
| ------------------------------- | ------------------------- |
| “per user/per day/per category” | GROUP BY                  |
| “top/highest/rank”              | ORDER BY + WINDOW         |
| “latest record”                 | ROW_NUMBER                |
| “without orders/no activity”    | LEFT JOIN                 |
| “more than average”             | SUBQUERY                  |
| “running total”                 | WINDOW FUNCTION           |
| “last 30 days”                  | DATE                      |
| “duplicate”                     | GROUP BY + HAVING         |
| “hierarchy”                     | SELF JOIN / RECURSIVE CTE |



# Actual SQL Execution Order
1. FROM
2. JOIN
3. WHERE
4. GROUP BY
5. HAVING
6. SELECT
7. DISTINCT
8. ORDER BY
9. LIMIT
