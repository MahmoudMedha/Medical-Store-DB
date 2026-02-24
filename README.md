# Medicine Store Database Project
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

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

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/IbraheemSultan"><img src="https://avatars.githubusercontent.com/u/70492711?v=4?s=100" width="100px;" alt="Ibraheem Mohammed Abd El-Twab Mohammed"/><br /><sub><b>Ibraheem Mohammed Abd El-Twab Mohammed</b></sub></a><br /><a href="https://github.com/IbraheemSultan/Medical-Store-DB/commits?author=IbraheemSultan" title="Tests">⚠️</a> <a href="https://github.com/IbraheemSultan/Medical-Store-DB/commits?author=IbraheemSultan" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/MahmoudMedha"><img src="https://avatars.githubusercontent.com/u/208298621?v=4?s=100" width="100px;" alt="Mahmoud Medhat Mohamed"/><br /><sub><b>Mahmoud Medhat Mohamed</b></sub></a><br /><a href="https://github.com/IbraheemSultan/Medical-Store-DB/commits?author=MahmoudMedha" title="Documentation">📖</a> <a href="https://github.com/IbraheemSultan/Medical-Store-DB/commits?author=MahmoudMedha" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!