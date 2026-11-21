# Project_Template_ComputerScience2

# 📊 Data Insights Dashboard Project

# BaonBuddy Expense Log

## Cache Me If You Can (8 - Dahlia, Group 1)
* Ervic Cansancio
* Vidal Diuyan III
* Jaydeen Danielle Lagrimosa
* Jarvis Larkin Yee
* Danielle Lakshmi Escleto
* Daniella Yen Salcedo

---

### a. What problem are you trying to solve?
Many high school students struggle to keep track of their daily school allowance (*baon*) and small everyday expenses like food, commuting fares, and school supplies. Because they often rely on memory or scattered notes, they may overspend early in the week and run short on money before Friday. **BaonBuddy Expense Log** solves this by providing a simple console application where students can log their allowances and expenses in one organized place and check their remaining balance anytime.

### b. What are your app's features? How does the app help solve the problem?
* **Add Transaction (Create):** Log a new allowance or expense entry with its amount, category, and date.
* **View & Search Records (Read):** Browse all saved transactions or filter entries by category or date to see where money was spent.
* **Edit Transaction (Update):** Fix mistakes in previously recorded amounts, categories, or notes.
* **Delete Transaction (Delete):** Remove duplicate or invalid entries from the log.
* **Budget Summary & Insights:** Automatically calculate total allowance received, total expenses, remaining balance, daily average spending, and the highest-spending category.

All records are saved persistently in a JSON file so users can track their spending habits across multiple school days and weeks.

### c. What specific data will you handle?
* **Transaction ID:** Unique identifier for each entry (used to search, edit, and delete specific records).
* **Type:** Indicates whether the entry is an `Allowance` (income) or `Expense`.
* **Category:** Classifies the transaction (e.g., *Food*, *Commute*, *School Supplies*, *Daily Baon*, *Savings*).
* **Amount:** The monetary value in Philippine Pesos (₱).
* **Date:** The date of the transaction (`YYYY-MM-DD`) to track daily and weekly trends.
* **Description / Note:** Short details about the item or expense (e.g., *"Lunch at canteen"* or *"Jeepney fare"*).
