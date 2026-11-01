# SQL SELECT Statements — Learning Reference

**Status:** Educational example; not a verified independent SQL exercise.

## Explanation
`SELECT` retrieves chosen columns from a table. `ORDER BY` makes output order deterministic for this example.

## Syntax
```sql
SELECT column_name
FROM table_name
ORDER BY column_name;
```

## Reproducible Synthetic Dataset (SQLite)
```sql
CREATE TABLE customers (
    customer_id INTEGER PRIMARY KEY,
    customer_name TEXT NOT NULL
);
INSERT INTO customers (customer_id, customer_name) VALUES
(101, 'Alex Taylor'),
(102, 'Jordan Lee'),
(103, 'Morgan Davis');
```

## Example Query
```sql
SELECT customer_id, customer_name
FROM customers
ORDER BY customer_id;
```

## Expected Output
| customer_id | customer_name |
|---:|---|
| 101 | Alex Taylor |
| 102 | Jordan Lee |
| 103 | Morgan Davis |

## Explanation
The query selects two columns from the synthetic table and sorts by customer ID ascending.

## Practice Problems (Not Yet Completed)
1. Select only `customer_name`.
2. Return records in descending `customer_id` order.
3. Retrieve the record for customer 102 using `WHERE`.

Record the database version, actual outputs, and debugging notes after executing exercises.

## Common Mistakes
Incorrect table or column names; missing commas; assuming row order without `ORDER BY`.

[← SQL Practice](../README.md)
