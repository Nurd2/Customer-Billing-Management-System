# Customer-Billing-Management-System

# Customer Billing Management System

A simple terminal-based application written in C to manage customer phone usage and billing. It demonstrates fundamental C programming concepts such as structs, arrays, string handling, and modular function design.

---

## Repository Structure

```
Customer-Billing-System/
├── main.c           # Core program source code
├── README.md        # Project overview and instructions
├── .gitignore       # Common C/C++ ignores (e.g., object files)
└── LICENSE          # Project license (MIT)
```

---

## 🚀 Features

* **Structs & Arrays**: Uses a `Customer` struct and an array to store up to 100 records.
* **CRUD Operations**:

  * **Create**: Add new customer records with name, phone number, and usage.
  * **Read**: View all customer records in a formatted list.
  * **Update**: Modify usage details for an existing customer.
  * **Delete**: Remove a customer record by phone number.
* **String Handling**: Searches and compares customer phone numbers using `strcmp()`.
* **Menu-Driven Interface**: User-friendly console menu for navigating operations.
* **Simple Billing Logic**: Calculates total bill at \$0.10 per usage minute.

---

## Prerequisites

* GCC or any C compiler
* Basic familiarity with the command line

---

## Installation & Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/<your-username>/Customer-Billing-System.git
   cd Customer-Billing-System
   ```

2. **Compile the program**:

   ```bash
   gcc -o billing main.c
   ```

3. **Run the application**:

   ```bash
   ./billing
   ```

4. **Follow on-screen menu** to add, view, modify, or delete records.

---

## 📖 Function Overview

| Function         | Description                                             |
| ---------------- | ------------------------------------------------------- |
| `addRecord()`    | Prompt user to input customer details and add to array. |
| `viewRecords()`  | Display all current customer records.                   |
| `modifyRecord()` | Update usage and bill for a customer by phone.          |
| `viewPayment()`  | Show billing details for a specific customer.           |
| `deleteRecord()` | Remove a customer record from the array.                |
| `displayMenu()`  | Print the main menu options.                            |

---

## 📜 License

This project is released under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve features or add new ones.
