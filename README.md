# 🛒 PANTRY PRIDE GROCERIES - Store Management System using apriori algorithm

A full-featured **Python-based desktop application** for managing retail operations including billing, inventory management, user login, data analytics using the Apriori algorithm, and interactive data visualization.

---

## 📌 Key Features

### 🧾 Billing & POS
- Add items to a shopping cart
- Apply discounts and generate receipts
- Auto print bills (with date-stamped folder organization)
- Real-time stock updates
- Combobox product selection and live search

### 📦 Inventory Management
- Add and update products with vendor details
- Calculate cost price, selling price, profit, etc.
- Vendor phone validation
- SQLite database for persistent storage (`amart.db`)

### 🔐 Role-Based Authentication
- Separate logins for **owner** and **employee**
- Username/password validation via `.txt` files
- Option to update credentials securely
- Regex-based password strength validation

### 📊 Data Analysis (Apriori Algorithm)
- Frequent itemset mining with support & lift metrics
- Generates association rules (market basket analysis)
- Summary tables displayed in the GUI

### 📈 Data Visualization
- Support vs Confidence scatter plot
- GUI-embedded Matplotlib visualizations

---

## 🛠️ Technologies Used

- **Python**
- **Tkinter** (GUI)
- **SQLite3** (Database)
- **Pandas**, **MLxtend**, **Matplotlib**
- **CSV** for transaction logging

---


---

## ✅ Login Info

Stored in `owner1.txt`, `owner2.txt`, `emp1.txt`, `emp2.txt`  
Update credentials via the GUI under "OwnLogin Update" and "EmpLogin Update" tabs.

---

SAMPLE DATASET:
bill,product,quantity
1001,Milk,2
1001,Bread,1
1002,Eggs,12
...

