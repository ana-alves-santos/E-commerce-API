# 🛒 E-commerce API – Study Project with Flask

> ℹ️ This project comes with a pre-filled database containing a **user, product, and cart**, ideal for quick testing with Postman or Insomnia.

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

## 🧾 Example Database (`ecommerce.db`)

This project includes a pre-populated SQLite database with the following data to facilitate testing:

### 👤 Test User:

| Field    | Value    |
|----------|----------|
| username | `admin`  |
| password | `123`    |

---

### 📦 Registered Product:

| ID | Name | Price | Description     |
|----|------|-------|-----------------|
| 2  | TV   | 1000  | 4K Smart TV     |

---

### 🛒 Initial Cart:

- The product “TV” is already added to the `admin` user's cart.

---

## 🛠 Technologies Used

- **Python 3**  
- **Flask**  
- **Flask-Login**  
- **Flask-CORS**  
- **SQLAlchemy**  
- **SQLite**  
- **Swagger (YAML)**  
