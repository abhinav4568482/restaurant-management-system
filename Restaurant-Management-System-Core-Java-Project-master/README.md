<img width="1098" height="675" alt="Screenshot 2025-08-12 194156" src="https://github.com/user-attachments/assets/dfc7bd19-8318-42c5-a693-ce12b5a3d21f" />

# Restaurant Management System 

## 📌 Overview
A Java-based Restaurant Management System with a graphical interface that allows managers and staff to handle menu items, employee details, and customer orders efficiently.

---

## 🔐 Login
For first-time use, you can log in using the sample credentials below.  
Managers can add new staff members from within the application.

### **Manager Accounts**
- **ID:** `1000` &nbsp; **Password:** `Java`
- **ID:** `5555` &nbsp; **Password:** `kazukazu`

### **Staff Accounts**
- **ID:** `1111` &nbsp; **Password:** `password`
- **ID:** `3333` &nbsp; **Password:** `david`

> ⚠️ Directly modifying the data files is not recommended as it may cause system issues.

---

## 🍽 Viewing the Menu
- Click **ALL** to view all available menu items.  
- Use category buttons (**Drink**, **Alcohol**, **Main**, **Dessert**) to filter menu items by type.

---

## 📝 Taking Orders

### Creating a New Order
1. Click **Show Menu** in the left panel.  
2. Click **New** to create a new order.  
   ![](readme_images/order.jpg)
3. Select menu items from the list on the right.  
4. Enter the quantity and click **Add**. (If left blank, quantity defaults to 1.)  
5. To remove an item, select it from the order details and click **Delete**.

---

### Editing an Existing Order
1. Click **Show Menu** in the left panel.  
2. Select the order from the list.  
3. Click **Edit**.  
4. Add or remove items as needed.

---

### Closing or Canceling an Order
1. Select the order from the list.  
2. Click **Close** or **Cancel**.  
3. Once closed or canceled, an order cannot be edited.

---

## 👥 Employee Management *(Manager Only)*

### Adding a New Staff Member
1. Click **Manage Employees**.  
2. Click **New**.  
3. Fill in the required details and click **OK**.

### Editing Staff Details
1. Click **Manage Employees**.  
2. Select a staff member from the list.  
3. Click **Edit**, update details, and click **OK**.

### Deleting a Staff Member
1. Click **Manage Employees**.  
2. Select a staff member.  
3. Click **Delete**.

---

## 📋 Menu Item Management *(Manager Only)*

### Adding a New Menu Item
1. Click **Manage Menu Items**.  
2. Click **Add New Menu Item**.  
3. Fill in details and click **OK**.

### Editing a Menu Item
1. Click **Manage Menu Items**.  
2. Select an item from the menu list.  
3. Click **Edit Menu Item**, make changes, and click **OK**.

### Deleting a Menu Item
1. Click **Manage Menu Items**.  
2. Select an item.  
3. Click **Delete Menu Item**.

---

## 📎 Notes
- This system uses preloaded sample data for demonstration purposes.
- Ensure that the Java environment (JDK) is installed before running the application.

##About payments
* When you log in, the system automaticaly set start working time.
* Clock out button will set finish working time of the person currently logged in.
* Manager can make staff clocked out via manage employees, by selecting staff and clicking Clock out button.
* You can see a payment details for a day by clicking "Show payment" button on the left 
