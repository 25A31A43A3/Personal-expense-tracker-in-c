Personal Expense Tracker (C)

A simple console-based Personal Expense Tracker developed in C. The application allows users to record expenses, view saved expenses, calculate total spending, and store data in a file for future use.

Features
Add new expenses with category and amount
View all recorded expenses
Calculate total expenses
Save expenses to a file
Load saved expenses automatically on startup
Menu-driven interface
Technologies Used
C Programming Language
Structures
File Handling
Arrays
Functions
Project Structure
Personal-Expense-Tracker/
│
├── main.c
├── expenses.txt
└── README.md
How It Works
Start the application.
Choose an option from the menu:
Add Expense
View Expenses
Show Total Expenses
Exit
Expense records are stored in expenses.txt.
Existing records are loaded whenever the program starts.
Compilation

Using GCC:

gcc main.c -o ExpenseTracker
Run

Linux/macOS:

./ExpenseTracker

Windows:

ExpenseTracker.exe
Sample Input
Enter category: Food
Enter amount: 250
Sample Output
Expense List

Category            Amount
Food                250.00
Transport           100.00

Total Expenses: 350.00
Future Enhancements
Monthly and yearly reports
Budget management
Expense editing and deletion
Search and filter functionality
Data visualization
Database support
Learning Outcomes

This project helps practice:

Structures in C
File Handling
Arrays
Functions
Menu-driven Programs
Data Persistence
