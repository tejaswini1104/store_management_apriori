🛒 Store Management System using apriori algorithm

A complete desktop-based Store Management System with billing, inventory control, analytics, and user management features built using **Python (Tkinter)**, **SQLite**, and **Apriori Algorithm** for sales analysis.

📌 Features

### 🧾 Billing System
- Add products to cart
- Apply discounts
- Auto-generate printable bills with transaction records
- Stock updates in real-time

### 📦 Inventory Management
- Add new products with cost/selling price
- Update existing product details
- Track vendor and contact information

### 📊 Sales Analytics
- Apply Apriori algorithm to find frequent itemsets and association rules
- Visualize product correlations
- Bar chart showing product conviction scores

### 👥 User Authentication
- Owner and Employee login system
- Password validation and update
- Role-based access to features


## 🛠️ Technologies Used

- **Python** (Tkinter for GUI)
- **SQLite** (for inventory and transaction storage)
- **CSV** (for transaction logs)
- **MLxtend** (Apriori algorithm and association rules)
- **Matplotlib** (bar chart plotting)
- **Regex** (for password validation)

  


## 🔐 Login Credentials

> 🔒 **Credentials stored in local `.txt` files.**

- **Owner login**:
  - `o1.txt` - username
  - `o2.txt` - password

- **Employee login**:
  - `e1.txt` - username
  - `e2.txt` - password

You can change them from the "Change Password" sections within the application.


## 🚀 How to Run

1. Ensure you have Python installed (recommended: 3.9+)
2. Install required libraries:
   ```bash
   pip install pandas matplotlib mlxtend

SAMPLE DATASET:
bill, product, quantity
101, Milk, 2
101, Bread, 1
102, Butter, 1
...


