# 🛵 Delivery App - Full Stack Project

A comprehensive food delivery system designed to manage restaurants, customers, and orders. This project was built to simulate the real-world workflow of a delivery application, enabling partner registration, multi-item order creation, and real-time status management.

## 🛠️ Tech Stack

### Frontend
* **React + Vite**: Framework for building fast and reactive user interfaces.
* **Tailwind CSS**: Modern and responsive utility-first CSS framework.
* **Axios**: Promise-based HTTP client for seamless Backend communication.
* **React Router Dom**: Routing management and SPA (Single Page Application) navigation.

### Backend
* **Node.js**: JavaScript runtime environment for server-side logic.
* **Express**: Fast and minimalist web framework for building the REST API.
* **MySQL (mysql2)**: Relational database management system.
* **MVC Architecture**: Code organized into Model, View, and Controller layers for better scalability.
* **Dotenv**: Environment variable management for security and configuration.
* **CORS**: Security configuration for cross-origin resource sharing.

---

## ✨ Key Features

* ✅ **Restaurant Management:** Register and list partners and cuisine types.
* ✅ **Customer Management:** User registration including delivery address details.
* ✅ **Order Placement:** Dynamic order creation with shopping cart functionality.
* ✅ **Status Control:** Real-time tracking and management of the delivery lifecycle.

---

## 📱 Usage Guide (Step-by-Step)

To test the application's complete workflow, follow these steps in the interface:

1. **Initial Setup:**
    * Navigate to the **Restaurants** tab and register a new establishment.
    * Navigate to the **Customers** tab and register a user.

2. **Placing an Order:**
    * Access the **Place Order** tab.
    * Select the Customer and the Restaurant you created.
    * Add items to the cart.
    * Click **Checkout**.

3. **Managing Status:**
    * Once finalized, the order will appear in the "Active Orders" list with a **Preparing** status (Yellow).
    * Click **"Dispatch for Delivery"** to change the status to **In Transit** (Blue).
    * Click **"Confirm Delivery"** to mark it as **Delivered** (Green).

---

## 🗄️ Database Configuration

This project uses **MySQL**. Before running the application, execute the `delivery.sql` script in your MySQL Workbench or terminal to set up the required schema and tables.

---

### 👨‍💻 Authors

- **João Pedro Soares Franco** - [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-pedro-franco-545436221/) - [GitHub](https://github.com/jotapz)
- **Lara Stephanny** - [LinkedIn](https://www.linkedin.com/in/lara-stephanny-0317a82b5/) - [GitHub](https://github.com/LaraSLGomes)
