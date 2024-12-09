
# ATM Simulation in C++  

## Project Overview  
This project simulates an Automated Teller Machine (ATM) using C++. It allows users to perform basic banking transactions such as withdrawing cash, depositing money, checking account balances, and logging into their accounts. The application is designed to provide a simple, console-based experience while illustrating fundamental object-oriented programming concepts.  

## Features  
- **User Authentication**: Users can log in using their account numbers and PIN codes.  
- **Account Management**: Users can view their account balances and transaction history.  
- **Cash Withdrawal**: Users can make quick or normal withdrawals from their accounts.  
- **Deposit Functionality**: Users can deposit funds into their accounts.  
- **Balance Check**: Users can check their current account balance.  
- **File Persistence**: User data is saved to a text file (`Clients.txt`), allowing for persistent data between sessions.  

## Project Structure  
- **sClient Struct**: Holds user account information, including account number, PIN, name, phone number, and balance.  
- **Main Menu**: Presents users with options to perform various transactions.  
- **Transaction Functions**: Implements the logic for deposit, withdrawal, and balance checks.  
- **File Handling**: Functions to load and save client data from/to a text file.  

