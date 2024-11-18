### **Banking Program**

This is a simple **Python-based banking program** that allows users to:
1. Check their account balance.
2. Deposit money.
3. Withdraw money.
4. Exit the program.

---

### **Features**
- **Show Balance**: Displays the current account balance, formatted to two decimal places.
- **Deposit Money**: Allows users to deposit a valid amount (greater than or equal to $0).
- **Withdraw Money**: Allows users to withdraw funds, ensuring the amount is greater than $0 and does not exceed the available balance.
- **Exit Program**: Safely exits the program.

---

### **How to Use**
1. Run the program by executing the `banking_program.py` file:
   ```bash
   python banking_program.py
   ```
2. Follow the on-screen menu:
   - **Option 1**: View your current balance.
   - **Option 2**: Enter an amount to deposit into your account.
   - **Option 3**: Enter an amount to withdraw from your account. Ensure you have sufficient funds.
   - **Option 4**: Exit the program.

---

### **Code Walkthrough**
1. **Main Functionality (`main`)**:
   - Handles the program's flow using a `while` loop.
   - Displays a menu for the user to select their desired action.
   - Processes user input and calls the appropriate function.

2. **Show Balance (`show_balance`)**:
   - Prints the current balance in a clear, formatted manner.

3. **Deposit Functionality (`deposit`)**:
   - Prompts the user to input a deposit amount.
   - Validates the amount (must be non-negative) and returns it to update the balance.

4. **Withdraw Functionality (`withdraw`)**:
   - Prompts the user to input a withdrawal amount.
   - Ensures the amount is valid (greater than 0 and less than or equal to the balance) before deducting it from the account.

---

### **Sample Output**
**Initial Menu**:
```
********************************
        Banking Program         
********************************
1. Show Balance
2. Deposit
3. Withdraw
4. Exit
********************************
Enter your choice (1-4):
```

**Deposit Example**:
```
Enter the amount to deposit: 100
********************************
Your balance is $100.00
********************************
```

**Withdraw Example**:
```
Enter the amount to withdraw: 50
********************************
Your balance is $50.00
********************************
```

**Invalid Input Example**:
```
Enter your choice (1-4): 5
**************************
That is not a valid choice
**************************
```

### **Requirements**
- Python 3.x

---

### **Author**
This program was created as a basic Python project to demonstrate programming concepts such as:
- User input handling
- Functions
- Conditional statements
- Loops
