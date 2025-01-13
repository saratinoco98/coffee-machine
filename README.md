☕ Coffee Machine Program
A Python-based coffee machine simulator that manages resources, handles transactions, and serves virtual coffee drinks. This program simulates a real coffee vending machine with multiple drink options and resource management.
🚀 Features

Multiple drink options (Espresso, Latte, Cappuccino)
Resource management system (water, milk, coffee)
Coin-operated payment system
Change calculation and return
Maintenance reporting system

📋 Requirements

Python 3.6 or higher

🎮 Usage
Run the program by executing:
bashCopypython coffee_machine.py
Available Commands:

espresso: Order an espresso ($1.50)
latte: Order a latte ($2.50)
cappuccino: Order a cappuccino ($3.00)
report: View current resource levels
off: Turn off the machine

🎯 How It Works

User selects a drink or enters a command
Program checks resource availability

If resources are sufficient:

User is prompted to insert coins
Payment is processed
Change is calculated and returned
Drink is prepared
Resources are updated

If resources are insufficient or payment fails:

Appropriate error message is displayed
Operation is cancelled
