# Financial Dashboard

A personal finance tracker that runs entirely in the browser — no server, no login, no data sent anywhere. Built as a single HTML file, deployable on GitHub Pages in minutes.

## Features

- **Income** — hourly, weekly, or bi-weekly jobs with tax % → calculates net take-home per week
- **Credit Cards** — enter balance, limit, APR → see effective interest rate; toggle between entering a weekly payment (shows weeks to payoff) or a target # of weeks (shows required payment)
- **Loans & Family Debts** — balance + weekly payment → weeks remaining
- **Bank Accounts** — track balances across checking, savings, and other accounts
- **Recurring Expenses** — weekly input auto-calculates monthly and annual totals
- **Summary Bar** — live net income, total debt payments, discretionary cash left over
- **Debt Payoff Timeline** — visual bar chart with estimated clearance date
- **Print One-Pager** — clean print layout, buttons hidden, everything on one page

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose `main` branch, `/ (root)` folder
5. Click **Save**

Your site will be live at `https://yourusername.github.io/repo-name` within a minute or two.

## Local Use

Just open `index.html` in any browser — no build step, no dependencies, no installation.

## Privacy

All data stays in your browser tab. Nothing is stored, transmitted, or tracked. Closing the tab resets everything.
