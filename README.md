# Personal_Expense_Tracker
**Personal Expense Tracker** is a simple **PHP &amp; MySQL-based** database management system for tracking daily expenses. It allows users to log income and expenses, categorize transactions, and generate summaries for better financial planning. 💰📊🚀
## 🚀 Features
- 💰 Add, edit, and delete transactions
- 📊 Categorize expenses and income
- 📅 View transaction history with date-wise filtering
- 📉 Generate financial summaries and reports
- 🔐 Secure user authentication (optional)
- 🎨 Responsive and user-friendly interface

## 🛠️ Technologies Used
- **PHP** - Backend logic and database interactions
- **MySQL** - Database management for storing transactions
- **HTML, CSS, JavaScript** - Frontend design and interactivity

## 📂 Project Structure
```
PersonalExpenseTracker/
│── index.php        # Main dashboard
│── add_expense.php  # Page to add a new expense
│── view_expenses.php# View transaction history
│── config.php       # Database connection
│── styles.css       # Styling file
│── script.js        # JavaScript for interactivity
└── database.sql     # Database schema
```

## 🚀 Getting Started
### 🔧 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/PersonalExpenseTracker.git
   ```
2. Navigate to the project folder:
   ```sh
   cd PersonalExpenseTracker
   ```
3. Import the database:
   - Create a MySQL database
   - Import `database.sql` into your database
4. Configure the database connection in `config.php`:
   ```php
   $servername = "localhost";
   $username = "your-username";
   $password = "your-password";
   $dbname = "your-database-name";
   ```
5. Start a local server (e.g., using XAMPP, WAMP) and run the project.

## 🎯 Usage
- Open `index.php` in a browser.
- Log income and expenses.
- View transaction history and summaries.

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the project:
- Fork the repository
- Create a new branch
- Submit a pull request


Happy Coding! 🚀
