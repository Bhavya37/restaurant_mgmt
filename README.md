# 🍽️ Restaurant Management System – Python Project

A command-line based Restaurant Management System built in Python.  
It includes user profiles, menu handling, ordering, bill generation, allergen info, and full data persistence.

---

## 🚀 Features

### 👤 User Profile System
- Create or update user profiles  
- Access profile using username  
- Saved in `user_profiles.csv`

### 📜 Menu System
- Items stored in `menu.csv`
- Name, price, allergens included
- Automatically written & loaded on program start

### 🛒 Ordering System
- Choose from Starters, Main Course, Desserts
- Multiple items + quantities supported
- Shows allergen details instantly
- Smart recommendations based on items

### 💸 Billing System
- 18% tax added
- Additional 20% discount if total > ₹1000  
- Auto-generated printed receipt

### 🧾 Order History
- Saves username, items, date, total price  
- Stored in `order_history.csv`

---

## 📁 File Structure
```
Restaurant_Mgmt.py
menu.csv
user_profiles.csv
order_history.csv
```

---

## 🛠️ Requirements
Install pandas:

```bash
pip install pandas
```

---

## ▶️ How to Run

```bash
python Restaurant_Mgmt.py
```

Then follow the menu:

```
1. Create/Update Profile
2. Access Profile
3. Place an Order
4. Exit
```

---

## 🧩 How Data is Saved
The program uses `atexit` to auto-save:

- User profiles → `user_profiles.csv`
- Order history → `order_history.csv`

Even if the program stops, your data stays safe.

---

## 🔮 Future Improvements
- Add GUI with Tkinter or PyQt  
- Admin dashboard  
- Inventory management  
- Payment gateway simulation  
- Replace CSV files with SQL database  

---
❤️ Author  
Developed by Bhavya ✨


