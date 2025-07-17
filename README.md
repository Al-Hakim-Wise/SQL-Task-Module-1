## SQL Query - Data Mining Task (Module 18)

This repository contains my completed SQL query for **Module 18 Task 2** from the Data Mining with SQL hands-on assignment.

### 📁 File Included:
- **SQLQuery.png** → Screenshot showing the SQL query and its result.

### 💻 Task Description:
The assignment required me to:
- Retrieve all **OrderDetails** records where **Quantity > 20**.
- Sort the results by **ProductID** in ascending order.

### ✅ SQL Code Used:
```sql
SELECT * FROM OrderDetails
WHERE Quantity > 20
ORDER BY ProductID;
