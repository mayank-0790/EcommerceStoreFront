# 🛒 E-Commerce Storefront

**React.js + Spring Boot Full Stack Application**

## 📌 Overview

This project is a **full-stack e-commerce storefront** built using **React.js (frontend)** and **Spring Boot (backend)**.
It allows users to browse products, add items to a cart, and place orders while the backend handles product management, authentication, and order processing through REST APIs.

The goal of this project is to demonstrate a **modern full-stack architecture** with a responsive frontend and a scalable backend.

---

## 🚀 Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* Axios
* React Router
* CSS / Tailwind / Bootstrap (optional)

### Backend

* Spring Boot
* Spring MVC
* Spring Data JPA
* Hibernate
* REST API

### Database

* MySQL / PostgreSQL

### Tools

* Maven
* Git
* Postman
* Node.js & npm

---

## 🏗️ Project Architecture

```
Frontend (React.js)
        |
        | REST API (Axios)
        ↓
Backend (Spring Boot)
        |
        ↓
Database (MySQL / PostgreSQL)
```

The React application communicates with the Spring Boot backend via **REST APIs** to fetch products, manage cart items, and handle orders.

---

## 📂 Project Structure

### Frontend (React)

```
frontend/
│
├── public/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── ProductCard.jsx
│   │   ├── Cart.jsx
│   │
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── ProductDetails.jsx
│   │   ├── Checkout.jsx
│   │
│   ├── services/
│   │   └── api.js
│   │
│   ├── App.jsx
│   └── main.jsx
```

### Backend (Spring Boot)

```
backend/
│
├── controller/
│   └── ProductController.java
│
├── service/
│   └── ProductService.java
│
├── repository/
│   └── ProductRepository.java
│
├── model/
│   └── Product.java
│
└── EcommerceApplication.java
```

---

## ✨ Features

### User Features

* Browse all products
* View product details
* Add / remove products from cart
* Checkout functionality

### Admin Features

* Add new products
* Update product details
* Delete products

### Backend Features

* RESTful APIs
* Database persistence with JPA
* Layered architecture (Controller → Service → Repository)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ecommerce-storefront.git
cd ecommerce-storefront
```

---

### 2️⃣ Backend Setup (Spring Boot)

Navigate to the backend folder:

```bash
cd backend
```

Run the application:

```bash
mvn spring-boot:run
```

Backend will start at:

```
http://localhost:8080
```

---

### 3️⃣ Frontend Setup (React)

Navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Run the React app:

```bash
npm run dev
```

Frontend will start at:

```
http://localhost:5173
```

---

## 🔗 API Endpoints

### Product APIs

| Method | Endpoint             | Description       |
| ------ | -------------------- | ----------------- |
| GET    | `/api/products`      | Get all products  |
| GET    | `/api/products/{id}` | Get product by ID |
| POST   | `/api/products`      | Add new product   |
| PUT    | `/api/products/{id}` | Update product    |
| DELETE | `/api/products/{id}` | Delete product    |

---

## 📸 Screenshots

Add screenshots of:

* Home page
* Product listing
* Cart page
* Checkout page

Example:

```
/screenshots/home.png
/screenshots/cart.png
```

---

## 🔒 Future Improvements

* User authentication (JWT)
* Payment gateway integration (Stripe / Razorpay)
* Order history
* Product search & filtering
* Admin dashboard
* Docker deployment

---

## 🤝 Contributing

Contributions are welcome!
If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Developed by **Mayank Rajput**
