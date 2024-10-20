#fintrack

This C++ and SQLite-based Finance Tracker is a console application that helps users manage their personal finances by tracking transactions, showing account balances, and enabling account management through a simple command-line interface. The application uses SQLite as the database for securely storing user data and transaction history.

Features
1. User Account Management
Login: Users can log into their existing account using their credentials. Successful login grants access to the finance tracking functionalities.
Register: New users can create an account. Each user is provided a dedicated table within the database to track their transactions.
Delete Account: Users can delete their account, along with all the associated transaction data from the database.
Exit: Users can safely exit the application.
2. Finance Tracking
Add Income: Users can input financial gains, which will be added to their total account balance.
Add Expenses: Users can input financial expenses, which will deduct from their total account balance.
Monthly Transactions Summary: Users can view all transactions made within a specific month.
3. Transaction Overview
The application provides a running total of the user's finances, updated after each transaction.
4. Database Management
SQLite is used for persistent storage of user information and transaction records.
Each user has their own table in the database where transactions are logged.
