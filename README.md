
# Pharmacy Management System

This is a Python-based Pharmacy Management System that provides a GUI interface for managing medicine inventory, processing sales, generating reports, and analyzing pharmacy operations. It supports role-based access control for administrators and pharmacists.

## Features

### 🧾 Inventory Management
- **Add Medicine**: Add new medicines with expiry date, category, price, and cost.
- **Update Medicine**: Modify quantity, price, and cost of existing medicines.
- **Remove Expired Medicines**: Automatically filters out expired items.
- **Display Inventory**: View current stock list.
- **Low Stock Report**: Identify medicines below a user-defined threshold.

### 💳 Sales & Customer Management
- **Process Sales**: Record customer purchases and reduce stock.
- **Customer History**: Track purchases linked to specific customers.

### 📈 Reporting
- **Expired Medicines**: View expired items moved from inventory.
- **Sales Report**: Generate detailed reports between date ranges.
- **Top K Medicines**: Display most-sold medicines.
- **Sales Trends**: Analyze monthly, quarterly, or yearly sales.
- **Profit Calculation**: Compute profit based on sale vs cost price.

### 🔐 User Management & Logging
- **Role-Based Access**: 
  - `admin`: Full access.
  - `pharmacist`: Limited to sales and inventory viewing.
- **Create Users**: Admins can register new users.
- **Logs**: Track login, logout, and all major actions.

