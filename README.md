# Ledger — Budget & Cash Flow Planner

A single-file, interactive budget and cash flow planner styled like a
classic accounting ledger. Enter your income and expenses, set a savings
goal, and see your net monthly balance, savings projection, and
months-to-goal calculated live in the browser — no install, no server,
no data leaves your machine.

## Features

- **Income & expense tracking** — enter monthly take-home pay and editable
  expense line items (add or remove as many as you need).
- **Live net balance** — automatically calculates income minus expenses,
  shown in green (surplus) or red (deficit).
- **Running tape** — a receipt-style sidebar that tallies every line item
  and the final net balance, like an old adding machine tape.
- **Savings goal projection** — set a target amount and a time window;
  the tool estimates how many months it will take to reach your goal at
  your current savings rate.
- **Trend chart** — a line chart visualizing projected cumulative savings
  over your chosen window.

## How to use

1. Open `budget-planner.html` in any modern web browser (Chrome, Safari,
   Firefox, Edge). Double-click the file, or drag it into a browser
   window.
2. Enter your **monthly take-home pay** at the top.
3. Edit the pre-filled **expense categories** (name and amount), or use
   **"+ Add line item"** to add your own (e.g., childcare, gym, debt
   payments). Remove any row with the **✕** button.
4. Set your **savings goal** amount and a **projection window** in months.
5. Read your results:
   - **Net monthly balance** — what's left after expenses.
   - **Running tape** — a full breakdown of income and every expense.
   - **Months to reach goal** — how long until you hit your target at
     the current pace.
   - **Chart** — your projected savings balance over time.

## Notes & limitations

- All data lives only in the browser tab for the current session.
  Refreshing or closing the page **resets everything** to the defaults —
  there is no save/load or persistent storage.
- Figures are for **planning and educational purposes only**, not
  professional financial advice. Consult a licensed financial advisor
  for decisions specific to your situation.
- Projections assume a **constant** monthly net balance; they don't
  account for irregular income, one-time expenses, inflation, or
  interest earned on savings.
- Requires an internet connection on first load to fetch fonts (Google
  Fonts) and the charting library (Chart.js via cdnjs). If those
  domains are blocked, the page still works but with fallback fonts and
  no chart.

## File

- `budget-planner.html` — the complete tool (HTML, CSS, and JavaScript
  in one file).
