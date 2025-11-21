## Expense Track Application

This project is a *Python-based Expense Tracker*built uising :
**Tkinter* for the graphical user interface (GUI)
**SQLite3* for the database
** tkcalendar* for data input 

The application allows users to *add,edit,delete,view,and manage daily expenses* easily.
## 🔧 FEATURES
###  ✔Add New Expense 
Users can enter details such as :
*Data
*Payee
*Description
*Amount 
Mode of payment(cash,credit card ,paytm,google pay,etc)
## ✔ View All Expenses
All stored expenses are displayed in a Treeview table with scrolling support 
## ✔ Edit Existing Expense 
Users can select an expense from the table and edit its details.
##  ✔Delete Expense
Allows deleting:
*A specific selected expense 
*All expense from the database 
## ✔ Convert Expense to Words
Reads the selected expense in the form of a sentence 
## ✔ Clear Input Fields 
Resets all input dields to default values 
## 🗂 Database Structure

The application uses an SQLite database named *Expense Tracker.db* with one table:

### *ExpenseTracker*

| Column Name   | Type     | Description                   |
| ------------- | -------- | ----------------------------- |
| ID            | INTEGER  | Primary key, auto-incremented |
| Date          | DATETIME | Date of the expense           |
| Payee         | TEXT     | Person or organization paid   |
| Description   | TEXT     | Reason for payment            |
| Amount        | FLOAT    | Amount spent                  |
| ModeOfPayment | TEXT     | Payment method                |

##🖥 User Interface Overview
### 📌*Main Sections*
1.*Data Entry Frame*-Input fields for entering expense details
2.*Buttons Frame -Buttons for actions like Add,Edit,Delete,Clear,etc.
3.*Table Frame*-Treeview showing stored expenses
### 📌*Fields in Data Entry*
#Date(via DateEntry widget)
#Payee(Entry box)
#Description(Entry box)
#Amount(Entry box)
#Mode of Payment (Dropdown menu)
## ▶How it Works 
1. On running the script,the app checks for the database.
2. If not found ,it automatically creates the *ExpenseTracker* table .
3. User enter deatils -clicks *Add Expense*-data is stored.
4. The table is refreshed and displays the updated list . 
 ## 📦Requirements 
 Make sure you have the following installed:
 ### 🔹Python Libraries 
 #tkinter(built-in)
 #sqlite3(built-in)
 tkcalendar(install via pip)
 ### Install tkcalendar
 bash
 pip install tkcalendar 
 ## ▶ Running the program
 Simply run the Python script:
 bash 
 python expense_tracker.py
The GUI window will open 
## 📝 Notes 
#The window size is fixed at 1200*550
#Background colors and fonts are customizable 
#Treeview automatically updates after any addition ,edit ,or deletion 
## 📌Future Improvements (optional)
#Export expenses to CSV or PDF
#Add category-based filtering 
#Add monthly or yearly expense summary 
#Add charts for visualization 
## 📄 License 
This project is open-source and free to modify.

### Developed using Python and Tkinter 🐍✨


