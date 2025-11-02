**Bank Management System**

A GUI-based Python application that allows you to manage customer bank accounts efficiently using an interactive interface. This project simulates basic banking operations such as adding, updating, deleting, depositing, withdrawing, and checking balances — all through a simple, user-friendly Tkinter interface.

---

**Features**

* **Add New Accounts:** Create and store customer account details such as Account Number, Name, Account Type, and Balance.

* **Update Account Records:** Modify existing customer data with ease.

* **Delete Accounts:** Remove customer details from the system securely.

* **Deposit and Withdraw Money:** Perform banking transactions directly through the GUI.

* **Check Account Balance:** Instantly view the current balance of any selected account.

* **Modern GUI Design:** Built using Tkinter with a clean, intuitive layout for seamless user experience.

---

**How it Works**

The application uses the following key technologies:

* **Tkinter:** For building the graphical user interface and interactive elements.

* **ttk (Themed Widgets):** To display customer data in an organized table format using Treeview.

* **MessageBox:** To handle alerts, confirmations, and messages for user interaction.

* **Python Core Logic:** To perform all backend operations such as data validation, transaction updates, and record management.

The main script, `BankManagementSystem.py`, manages all user inputs and dynamically updates account data in real-time. It does not require an external database, making it a standalone, lightweight system ideal for local record management and demonstration purposes.

---

**Functionalities**

The system supports the following operations:

* **Add Account:**

  * **Action:** Enter all account details (Account No, Name, Account Type, Balance) and click **Add**.
  * **Result:** The record is added to the table and displayed in the Customer Records section.

* **Update Account:**

  * **Action:** Select an existing record, edit details, and click **Update**.
  * **Result:** The account information is updated in the table.

* **Delete Account:**

  * **Action:** Select an account and click **Delete**.
  * **Result:** The selected record is removed from the database table.

* **Deposit Money:**

  * **Action:** Select an account, enter an amount in the balance field, and click **Deposit**.
  * **Result:** The entered amount is added to the current balance.

* **Withdraw Money:**

  * **Action:** Select an account, enter the amount to withdraw, and click **Withdraw**.
  * **Result:** The amount is deducted from the account balance (if sufficient funds are available).

* **Check Balance:**

  * **Action:** Select an account and click **Check Balance**.
  * **Result:** Displays the account holder’s balance in a message box.

* **Clear Fields:**

  * **Action:** Click **Clear** to reset all text fields.
  * **Result:** The form becomes blank and ready for new data entry.

---

**Prerequisites**

You must have **Python 3.x** installed on your system.
Tkinter is included by default in most Python distributions.

---

**Installation**

1. **Clone the repository:**

   ```sh
   git clone https://github.com/YourUsername/Bank_Management_System.git
   cd Bank_Management_System
   ```

2. **Run the application:**

   ```sh
   python BankManagementSystem.py
   ```

---

**Usage**

After running the program, a GUI window will appear.
Use the **left panel** to input account details and perform actions such as Add, Update, Delete, Deposit, Withdraw, and Check Balance.
The **right panel** displays all stored customer records in a table view.

---

**Contributing**

Contributions are welcome! If you’d like to enhance this project or add new features, feel free to fork the repository, make your changes, and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

**License**

This project is open-source. See the LICENSE file for more information.

---

**About Author**

* **Boby Chauhan**

* MCA Data Science Student at University Institute of Computing (UIC), Chandigarh University, Mohali, Punjab – 140301

* **UID:** 25MCD10010

* **Semester/Year:** 1/1
