# 💊 Pharmacy Management System

A GUI-based Pharmacy Management System built with Python and Tkinter. It manages medicine inventory, sales, customers, reports, and user roles (admin/pharmacist).

---

## 🚀 Features

### Admin
- Add, update, and remove expired medicines
- Generate sales reports by date range
- Analyze sales trends (monthly, quarterly, yearly)
- Calculate profits
- Monitor low-stock items
- Create users with role-based access
- View activity logs
- Search medicines by name/category
- View top-K selling medicines
- Check customer history

### Pharmacist
- View inventory
- Process medicine sales

---

## 📂 File Structure

| File               | Description                          |
|--------------------|--------------------------------------|
| `pharmacy_management_system.py` | Main application file          |
| `inventory.txt`    | Stores medicine information          |
| `sales.txt`        | Records sales transactions           |
| `customers.txt`    | Customer purchase records            |
| `expired_med.txt`  | Archived expired medicines           |
| `users.txt`        | User credentials (username, hash, role) |
| `logs.txt`         | Logs of system activities            |
| `error.txt`        | Error logs for debugging             |

---

## 🛠️ Requirements

- Python 3.x
- Tkinter (comes with Python standard library)

---

## ▶️ How to Run

1. Make sure Python is installed on your system.
2. Place all required files in the same folder.
3. Run the system:

```bash
python pharmacy_management_system.py
```

---

## 🔐 User Roles

### Admin
Full access to all features.

### Pharmacist
Limited to viewing inventory and processing sales.

---

## 🔒 Authentication

- Users must log in using a username and password.
- Passwords are stored using SHA-1 hashing.

---

## 📘 Data Formats

### inventory.txt
```
name,quantity,price,expiry,category,cost
```

### sales.txt
```
YYYY-MM-DD,medicine_name,quantity,total
```

### users.txt
```
username,hashed_password,role
```

---

## 👤 Example Users

Add users manually in `users.txt` or use the "Create User" option (admin only).

Example:
```
amr,40bd001563085fc35165329ea1ff5c5ecbdbbeef,admin
john,40bd001563085fc35165329ea1ff5c5ecbdbbeef,pharmacist
```
*(Both passwords = `password`, SHA1 hashed)*

---

## 📌 Notes

- The app creates all required `.txt` files if not present.
- All actions and errors are logged.
- Inputs are validated for correctness.

---

## Example Use Cases

## User Authentication
## Admin
![image](https://github.com/user-attachments/assets/11df681d-c1e0-47c4-9a2c-9598acbe2b94)
![image](https://github.com/user-attachments/assets/c9fd273c-3b37-489d-8325-e4226cef5995)
## Pharmacists
![image](https://github.com/user-attachments/assets/f09eaf74-ed75-4da6-8bd1-45bcbdd181a0)
![image](https://github.com/user-attachments/assets/df8eb630-6b93-46af-bb53-8195a150701f)
## Display Inventory
![image](https://github.com/user-attachments/assets/ad6d9989-5a8f-486a-83bc-bb87bfe091a6)
## Show Expired Medicines
![image](https://github.com/user-attachments/assets/c622c358-da0b-4304-9324-ab0d6aa2b8e4)
## Low Stock Report
![image](https://github.com/user-attachments/assets/90894cdf-02a4-48a9-b779-34c091198ad0)
![image](https://github.com/user-attachments/assets/9345abfd-e16f-47f1-8ec8-27baf0b2378f)
## view log
![image](https://github.com/user-attachments/assets/51404441-863d-4547-93f1-debd01d213a5)










