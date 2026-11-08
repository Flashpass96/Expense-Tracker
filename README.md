Expense Tracker

A simple expense tracker built with HTML, CSS, and vanilla JavaScript. Add income and expenses, see your running balance, and keep your data between visits. No backend, accounts, or dependencies required.

Features
Add transactions with a description and an amount (positive for income, negative for expenses)
Live balance, total income, and total expenses, formatted as US dollars
Transaction history shown newest first, with income and expenses styled differently
Delete any transaction with one click
Data saved in the browser with localStorage, so it is still there after a refresh
Getting Started
Clone the repository:
bash
   git clone https://github.com/Flashpass96/Expense-Tracker.git
Open the folder and double-click index.html to run it in your browser.

No build step or installation is needed.

How to Use
Enter a description, such as "Groceries" or "Salary".
Enter an amount. Use a negative number for an expense (for example -45) and a positive number for income (for example 1200).
Click Add Transaction. The list, balance, income, and expenses update right away.
Click the x next to a transaction to delete it.
Project Structure
Expense-Tracker/
├── index.html   # Page structure and form
├── style.css    # Styling
└── script.js    # App logic and localStorage handling
What I Practiced
Handling form submissions with event listeners and preventDefault
Rendering and updating the DOM dynamically from an array of data
Using reduce and filter to calculate the balance, income, and expenses
Formatting currency with Intl.NumberFormat
Saving and loading data with localStorage and JSON
Possible Improvements
Categories and filtering
Editing existing transactions
Choosing the currency
Exporting data to CSV
Tech Stack

HTML5, CSS3, JavaScript (vanilla), Google Fonts (Poppins)
