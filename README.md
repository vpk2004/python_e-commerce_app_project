streamlit-app-project


Project Name: E-Commerce Online Management Application

Objective:
           * Develop a web-based application using Streamlit to manage customer requests for quotes (RFQs) in an e-commerce platform. The application will allow customers to request quotes for products, and the admin can manage, approve, or reject them.

          * This Python script implements a **Streamlit-based E-Commerce application** that integrates with a **MySQL database** to manage customers, employees, products, and orders. The application features a user-friendly interface with separate functionalities for customers and employees.
**Customer Features:**
1. Signup:
    Allows customers to register by entering personal details like name, date of birth, gender, email, phone number, city, and state.
    Provides username and password creation with validation for password confirmation.

2. Login:
   Customers can log in using their unique credentials (customer ID, username, and password).
      After logging in, customers can:
      View their order history.
      Place new orders by browsing products and selecting quantities.
      Cancel existing orders.
      Update personal details such as name, email, phone number, and address.

3. Order Management:
    Customers can view all their orders with details such as product name, quantity, and total price.
    Supports order placement and cancellation, with automatic stock updates in the database.

 **Employee Features:**
1. **Signup:**
   - Employees can register with a unique name, password, and phone number.

2. Login:
    Employees log in with their credentials to access product management features:
      Add new products to the inventory.
      Update product details such as name, quantity, and price per unit.
      Modify inventory levels based on new stock or sales.

**Admin Features (Employee Login):**
 Employees with admin privileges can:
 
   Manage the product catalog.
   Update inventory levels.
   Ensure accurate pricing of products.

**Database Integration:**

 The application connects to a MySQL database (online_store_management_system) for secure and efficient data storage and retrieval.
 Key database tables include:
   **Customer**: Stores customer details.
   **Employee**: Stores employee credentials and details.
   **Products**: Stores product details like name, quantity, and price.
   **Orders**: Tracks customer orders with product details and order statuses.

 **UI Elements:**
 
 **Streamlit Sidebar Navigation**: Allows switching between customer and employee sections.
 **Option Menus**: Enables intuitive navigation within customer and employee functionalities.
 **Interactive Forms**: Collects input for actions like signup, login, and order placement.
 **Tables**: Displays order details and product lists.

**Other Features:**

 **Dynamic Content Updates**: Real-time updates for stock changes, order placements, and cancellations.
 **Error Handling**: Validates user inputs and provides feedback for incorrect or incomplete information.
 **Visual Enhancements**: Includes headers, subheaders, and images to improve user engagement.

This application is ideal for small-to-medium e-commerce platforms looking for a lightweight, interactive, and easy-to-use solution for managing online sales and inventory.
