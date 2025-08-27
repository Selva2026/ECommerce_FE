# 🛍️ FSD E-Commerce Frontend (React + TailwindCSS)

This is a full-featured **E-Commerce Frontend Application** built using **React.js**, **TailwindCSS**, **Axios**, and **Context API**.  
It supports **authentication, cart, admin dashboard**, and **Stripe payment integration**.

### 🔗 Live Demo  
[https://fantastic-vacherin-9a81de.netlify.app/](https://fantastic-vacherin-9a81de.netlify.app/)

---

## ⚙️ Tech Stack

- React.js
- TailwindCSS
- Context API
- Axios
- React Router DOM
- Vite

---

## 🧠 Features

- ✅ **User Registration & Login**
- ✅ **Role-based Access (Admin/Customer)**
- ✅ **JWT Authentication**
- ✅ **Product Listing (Public)**
- ✅ **Cart System** (Add/Remove + Quantity Update)
- ✅ **Stripe Payment Integration**
- ✅ **Admin Dashboard**
  - Add / Update / Delete Products
  - View and Manage Orders
- ✅ Fully **responsive UI** using TailwindCSS

---

## 📁 Project Structure

```
├── src/
│   ├── components/         # Navbar, ProtectedRoute
│   ├── context/            # AuthContext
│   ├── pages/              # Home, Login, Register, Cart, AdminDashboard, Orders
│   ├── App.jsx             # Main Router Setup
│   └── main.jsx            # ReactDOM rendering
├── public/
├── tailwind.config.js
└── vite.config.js
```

---

## 🧪 Pages Overview

| Route          | Description                       | Access       |
|----------------|-----------------------------------|--------------|
| `/`            | Product Listing                   | Public       |
| `/login`       | Login Page                        | Public       |
| `/register`    | Register Page                     | Public       |
| `/cart`        | View & Manage Cart                | Customer     |
| `/order`       | View Order History + Stripe       | Customer     |
| `/admin`       | Admin Dashboard for management    | Admin Only   |

---

## 🔐 Auth Flow

- After login, user token is stored in **localStorage**
- Context API (`AuthContext`) handles auth state
- Routes are protected using **role-based redirects**

---


