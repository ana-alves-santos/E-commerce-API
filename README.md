# 🛒 E-commerce API – Study Project with Flask

---

## 📋 Description

E-commerce API developed with Flask as a study project. Allows user login, product management, shopping cart, and checkout operations, with user authentication.

---

## 🚀 Features

### 👤 Authentication
- `POST /login` – User login  
- `POST /logout` – User logout  

### 📦 Products
- `GET /api/products` – List all products  
- `GET /api/products/<product_id>` – View product details  
- `POST /api/products/add` – Add new product *(auth required)*  
- `PUT /api/products/update/<product_id>` – Update product *(auth required)*  
- `DELETE /api/products/delete/<product_id>` – Delete product *(auth required)*  

### 🛒 Shopping Cart
- `GET /api/cart` – View cart items *(auth required)*  
- `POST /api/cart/add/<product_id>` – Add product to cart *(auth required)*  
- `DELETE /api/cart/remove/<product_id>` – Remove product from cart *(auth required)*  
- `POST /api/cart/checkout` – Complete purchase and clear cart *(auth required)*  

---

## 🛠 Technologies Used

- Python 
- Flask
- Flask-Login
- SQLAlchemy
- SQLite
- Postman (for testing)
- Swagger (YAML)


This project was developed during a Rocketseat course.
