# Store API Documentation

## Overview

Welcome to the **Store API** documentation. This API provides essential functionality for managing various aspects of an e-commerce platform, including user authentication, shopping cart management, product inventory, order management, and category management.

## Functionalities

### **Cart Management**
The API allows you to manage the shopping cart. This includes adding, updating, retrieving, and deleting cart items. You can interact with the entire cart or specific items within the cart, based on your needs.

### **Category Management**
You can manage product categories, including retrieving all categories, adding new categories, updating existing categories, and deleting categories. The system also provides the option to fetch categories with or without their related data.

### **Product Management**
The API enables the management of products in the system. You can add new products, update existing ones, retrieve product details, and remove products from the inventory.

### **Order Management**
The order management system allows you to place new orders, retrieve order details, update the status of orders, and view the products associated with a particular order. Users can view their past orders and track their status.

### **File Upload**
Users can upload files related to their orders or accounts through the file upload functionality.

### **User Authentication and Management**
This API supports user registration, login, and retrieving details of the currently logged-in user. Users can securely authenticate and manage their profile data.

---

## Data Models (Schemas)

### CartItem
Represents the details of items in a shopping cart.

### Category
Contains details about a product category, including its name, description, and any associated data.

### Product
Represents product details, including product name, description, price, and stock information.

### Order
Contains information about an order, including the products in the order, order status, and timestamps.

### User
Represents user information, including personal details, login credentials, and session data.

---

## Swagger UI

The API documentation is accessible through Swagger UI for easy interaction with the endpoints:

- **Swagger URL**: [https://localhost:7205/swagger/v1/swagger.json](https://localhost:7205/swagger/v1/swagger.json)

---

## Authentication

Some endpoints require user authentication. Use the **login functionality** to authenticate and obtain a token for making authorized requests.


