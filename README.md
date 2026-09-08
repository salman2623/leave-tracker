# Leave Tracker
A simple iPhone-friendly leave calendar based on the supplied Expense Tracker app.

## Features
- Current-year calendar with weekends automatically disabled as holidays
- Two leave types: Offshore and Onshore
- Tap any weekday to add/edit leave
- Current-date status: shows whether leave is still to be applied or excess leave has been taken
- Configurable annual leave allowance and required working days
- Year navigation and Today button
- Local browser storage; no server/database
- JSON backup and restore
- PWA / GitHub Pages / iPhone Home Screen support

## Calculation
For the current year, the app estimates leave that should have been used by today by spreading the annual allowance across the year's weekdays. It compares that expected amount with leave actually logged.
