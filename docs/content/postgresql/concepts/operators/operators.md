---
Title: 'Operators'
Description: 'Learn about PostgreSQL operators, which are symbols used to perform operations on one or more operands.'
Subjects:
 - 'PostgreSQL'
Tags:
 - 'SQL'
 - 'Database'
CatalogContent:
 - 'learn-postgresql'
 - 'paths/full-stack-engineer-career-path'
 - 'paths/data-engineer-career-path'
 - 'paths/data-scientist-career-path'
---

[**Operators**](https://www.postgresql.org/docs/current/sql-expressions.html#SQL-SYNTAX-OPERATORS) in PostgreSQL are symbols used to perform operations on one or more operands. They can be used in various contexts, such as arithmetic operations, comparisons, and logical operations.

## Syntax

Operators in PostgreSQL can be categorized into several types, including arithmetic operators, comparison operators, logical operators, and more. They are often used in combination with a `WHERE` clause.

- Arithmetic operators: `+`, `-`, `*`, `/`, `%`
- Comparison operators: `=`, `<>`, `<`, `>`, `<=`, `>=`
- Logical operators: `AND`, `OR`, `NOT`

### Arithmetic operators

Consider the following example that demonstrates the use of various operators in a PostgreSQL query:

#### Example

```
-- 
SELECT * FROM courses WHERE start_date > '10/10/2024'
```