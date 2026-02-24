# Medicine Store Database Project

A simple SQL Server schema and seed data for a medicine store database. The scripts create tables, insert sample data, and run basic queries to inspect the data.

## Files

- Quary_Project.txt: Full schema, sample inserts, and example selects.
- SQLQuery2.sql: Alternate script with similar schema and data.

## Database Schema (Summary)

- Customer, Custm_Phone
- Orders
- Suppliers, Supplier_Phone
- Products, Supplier_Productes
- Product_Check

## Setup (SQL Server)

1. Open one of the scripts in SQL Server Management Studio.
2. Execute the script to create the database and tables.
3. Run the insert statements to load sample data.
4. Use the select statements at the bottom to verify contents.

## Notes

- The scripts use `bit` flags for customer type fields (individual, hospital, pharmacy).
- The `Product_Check` table is updated based on order amount vs. product stock.

## 👥 Contributors

<!-- ALL-CONTRIBUTORS-BADGE: START -->
<!-- ALL-CONTRIBUTORS-BADGE: END -->

<!-- ALL-CONTRIBUTORS-TABLE: START -->
<!-- ALL-CONTRIBUTORS-TABLE: END -->
