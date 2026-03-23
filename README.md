# 🛒 Smart E-Commerce Web Application

## 📌 Project Overview

This is a full-stack e-commerce web application that displays products dynamically from a MySQL database. The project demonstrates backend API development using Node.js and Express, and frontend integration using HTML, CSS, and JavaScript.

---

## 🚀 Features

* 📦 View products from database
* 💻 REST API using Express.js
* 🗄️ MySQL database integration
* 🎨 Responsive frontend UI
* 🔄 Dynamic data fetching using Fetch API

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MySQL

---

## 📂 Project Structure

smart-ecommerce/
│
├── backend/
│   └── server.js
│
├── frontend/
│   └── index.html
│
└── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/Nishad21-NVG/smart-ecommerce.git

### 2️⃣ Backend Setup

cd backend
npm install
node server.js

### 3️⃣ Database Setup

Run the following SQL:

CREATE DATABASE ecommerce;
USE ecommerce;

CREATE TABLE products (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(255),
price INT,
category VARCHAR(100)
);

INSERT INTO products (name, price, category) VALUES
('Laptop', 60000, 'Electronics'),
('Phone', 20000, 'Electronics'),
('Shoes', 3000, 'Fashion'),
('T-shirt', 1000, 'Fashion');

### 4️⃣ Run Frontend

Open frontend/index.html in your browser

---

## 🌐 API Endpoint

GET /products
Fetch all products from database

---

## 📸 Output

Displays product cards with name, category, and price.

---

## 🔮 Future Enhancements

* 🛒 Add to Cart functionality
* 🔐 User Authentication (Login/Register)
* 💳 Payment Integration
* ⚛️ React Frontend

---

## 👨‍💻 Author

**Nishad Ghatage**
GitHub: https://github.com/Nishad21-NVG
