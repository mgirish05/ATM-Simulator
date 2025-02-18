# ATM-Simulator

A simple Python-based ATM simulator that allows users to check their balance, deposit money, and withdraw funds.

Features
- Check account balance
- Deposit funds
- Withdraw funds with insufficient balance check
- Simple text-based menu system

Technologies Used
- Python 3

## How to Run
1. Ensure you have Python installed on your system.
2. Download or clone this repository.
3. Open a terminal or command prompt and navigate to the project folder.
4. Run the script using:
   bash
   python atm.py
   
5. Follow the on-screen prompts to use the ATM.

Usage
When you run the script, you will see a menu:

1. Check Balance
2. Deposit
3. Withdraw
4. Exit

- Enter 1 to check your current balance.
- Enter 2 to deposit an amount into your balance.
- Enter 3 to withdraw an amount (if funds are sufficient).
- Enter 4 to exit the program.

Example Run

1. Check Balance
2. Deposit
3. Withdraw
4. Exit
Enter your choice: 1
Your account balance is $1000
Enter your choice: 2
Enter the deposit amount: 500
Deposited $500. Your new balance is $1500
Enter your choice: 3
Enter the withdrawal amount: 300
Withdrew $300. Your new balance is $1200
Enter your choice: 4
Thank you for using the ATM. Goodbye!


Future Enhancements
- Implement a PIN authentication system.
- Store transaction history.
- Use a database for persistent account storage.
- Add a graphical user interface (GUI).

