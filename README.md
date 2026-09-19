# PGMate – Hostel & PG Budget Tracker

## About the Project

PGMate is a modern, local-first budget tracker created for students and working professionals living in hostels, PGs, shared rooms, and co-living spaces. It turns everyday transactions into a clear plan for rent, food, bills, safe daily spending, and monthly savings.

## Problem Statement

Shared living comes with many small, frequent expenses that are easy to lose track of. PGMate helps hostel and PG residents understand where their money is going, control daily spending, split shared bills, and stay on course for a monthly savings goal.

## Features

- Monthly income and saving goal planning
- Dashboard cards for income, expenses, savings, goal, safe daily limit, and remaining budget
- Add, edit, delete, search, and filter expense transactions
- Current-month calculations with automatic remaining-day tracking
- Rent tracker with due date and paid/unpaid status
- Roommate bill splitter with per-person share calculation
- Smart budget alerts when spending is high or a saving goal is at risk
- Expense-by-category and savings progress visual analytics
- Monthly summary with highest category, average daily spend, and previous-month comparison
- Responsive navigation and empty states for a friendly experience on desktop and mobile
- LocalStorage persistence with no account or backend required

## Technologies Used

- HTML5
- CSS3 with responsive layout and custom properties
- Vanilla JavaScript
- Browser LocalStorage API
- HTML Canvas for lightweight analytics visuals

## How It Works

1. Set monthly income and a savings goal in the dashboard.
2. Add expenses with an amount, category, date, and description.
3. PGMate calculates current savings, remaining budget, and a safe daily spending limit using the current date.
4. Use the Expenses view to search or filter records and edit or delete them when needed.
5. Track rent, mark it paid, and use the roommate split tool for shared bills.
6. Review Analytics and Monthly Summary to spot your biggest spending categories and improve next month.

All information is saved in the browser's LocalStorage, so it remains available after a refresh on the same device and browser.

## Project Structure

```text
PGMate/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
```

## Future Improvements

- Export transactions to CSV or PDF
- Optional recurring expenses and bill reminders
- Multiple month archives and richer month-on-month charts
- Custom categories and currency preferences
- Optional cloud sync and sign-in
- Installable Progressive Web App support

PGMate was created to help hostel and PG residents manage expenses, control daily spending, and achieve monthly savings goals.
