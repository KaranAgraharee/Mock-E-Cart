# 🛍️ Mock E-Com Cart — Full-Stack Shopping Cart App

A simple full-stack **Mock E-Commerce Cart** built with **React**, **Express**, and **SQLite** for the Vibe Commerce internship assignment.  
It demonstrates a complete shopping cart flow — browsing products, adding/removing items, calculating totals, and performing a mock checkout — with smooth animations and responsive design.

---

## 🚀 Features
- 🧾 **Product Listing:** Displays mock products from backend database  
- 🛒 **Cart Management:** Add, remove, and update quantities  
- 💰 **Automatic Total Calculation** with dynamic updates  
- 💳 **Mock Checkout Flow:** Generates a fake receipt  
- 🌀 **Framer Motion Animations** for smooth UI transitions  
- 📱 **Responsive UI** (TailwindCSS)  
- ⚙️ **RESTful API Integration** using Express and SQLite  

---

## 🧩 Tech Stack

### **Frontend**
- ⚛️ React (Vite)
- 🎨 TailwindCSS
- 🌀 Framer Motion
- 🌐 Axios (for API calls)

### **Backend**
- 🚀 Node.js + Express
- 💾 SQLite (database)
- 🔓 CORS (for cross-origin requests)
- 🌱 dotenv (for environment variables)

---

## 📦 API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| **GET** | `/api/products` | Fetch all products |
| **GET** | `/api/cart` | Get all cart items + total |
| **POST** | `/api/cart` | Add item to cart `{ productId, qty }` |
| **DELETE** | `/api/cart/:id` | Remove item from cart |
| **POST** | `/api/cart/checkout` | Perform mock checkout & clear cart |

---

## ⚙️ Installation & Setup

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/mock-ecom-cart.git
cd mock-ecom-cart

cd backend
npm install
npm run start

cd ../frontend
npm install
npm run dev
