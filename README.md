# 🏦 ATM Simulator (Core Python Project)

## 📘 Overview
The **ATM Simulator** is a simple, command-line Python project that mimics real-world ATM operations such as account creation, deposits, withdrawals, balance checking, and transaction history.  
All user data is stored securely in a local **JSON file** for persistence — no external libraries are used, making it a **pure core Python project**.

---

## 🎯 Features
✅ Create new user accounts  
✅ Set and validate a 4-digit PIN  
✅ Deposit and withdraw money  
✅ Check current account balance  
✅ View transaction history  
✅ Data saved in a JSON file (`accounts.json`)  
✅ User-friendly command-line interface  

---

## 🧰 Technologies Used
- **Programming Language:** Python 3  
- **Concepts:**  
  - Object-Oriented Programming (OOP)  
  - File Handling (JSON)  
  - Loops & Conditional Statements  
  - Exception Handling  
  - Functions & Classes  

---

## ⚙️ How to Run the Project

1. **Create a folder** for your project (example):
   ```
   C:\Users\Neelima\Desktop\ATM_Simulator
   ```

2. **Save the file** `atm_simulator.py` inside this folder.

3. **Open Terminal / Command Prompt** in that folder and run:
   ```bash
   python atm_simulator.py
   ```

4. **Follow the menu options**:
   - Create an account (set your name and 4-digit PIN)
   - Login with your credentials
   - Perform deposit, withdrawal, or view balance/history
   - Logout safely

5. A file named `accounts.json` will be automatically created in the same folder to store account details.

---

## 🧾 Example Folder Structure
```
ATM_Simulator/
│
├── atm_simulator.py
└── accounts.json
```

---

## 📄 Sample JSON File Output
```json
{
    "Neelima": {
        "pin": "1234",
        "balance": 7500,
        "transactions": [
            "2025-11-13 09:01:12: Deposited ₹5000",
            "2025-11-13 09:05:23: Withdrew ₹2500"
        ]
    }
}
```

---

## 🧠 Learning Outcomes
By completing this project, you’ll gain hands-on experience with:
- Python OOP design  
- Data persistence using files  
- Command-line interfaces  
- Error and input handling  

