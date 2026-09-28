# Sam's Budget

A simple personal budget tracker for managing monthly income and everyday spending in Naira.

## What it does

- Starts with a **$650 monthly salary**, fully editable.
- Lets you set the **USD to NGN exchange rate** manually.
- Lets you add other monthly income and a monthly savings goal.
- Includes editable starter spending categories:
  - Transport
  - Feeding
  - Fuel
  - Bills & Utilities
  - Night Out / Fun
  - Gifts to Friends & Family
  - Debt Repayment
  - Airtime & Data
  - Rent / Housing
  - Health
  - Personal Care
  - Other
- Each category can be set as **per day, per week, or per month**.
- Converts daily and weekly amounts into an estimated monthly budget.
- Logs actual expenses by date, category, description, and Naira amount.
- Shows income, planned spending, actual spending, money left, category usage, and savings progress.
- Supports monthly history, editing and deleting expenses, and clearing a month.
- Supports JSON backup and restore.

## Data & privacy

The app uses browser local storage. No finance data is sent to a backend or database.

Because data lives in the browser, use **Export** occasionally to save a backup, especially before changing phones or browsers.

## Deploy to Vercel

This is a static site, so Vercel needs no build command or environment variables.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FKydosdigital%2Fsams-budget)

After importing the repository, Vercel should detect it as a static site and publish `index.html` from the repository root.
