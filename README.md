# INVOICE_GENERATOR
# 📄 Invoice Generation System

## 🚀 Overview

The **Invoice Generation System** is a full-stack web application that allows users to create, manage, and download professional invoices بسهولة. Built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**, this system simplifies billing by automating calculations, storing invoice data, and generating downloadable PDF invoices.

---

## ✨ Features

### 🧾 Invoice Management

* Create new invoices with customer details
* Add multiple items with price, quantity, and tax
* Automatic calculation of subtotal, tax, and total amount
* Generate and download invoices as PDF

### 📦 Item & Inventory Management

* Add, edit, and delete items
* Store item name, description, price, and tax rate
* Reuse saved items while creating invoices

### 💾 Data Storage

* Store invoices and item details in MongoDB
* Retrieve and manage past invoices

### 🔐 User-Friendly Interface

* Clean and responsive UI using React
* Easy navigation and form handling

---

## 🛠️ Tech Stack

**Frontend:**

* React.js
* HTML5, CSS3, JavaScript

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools:**

* Axios (API calls)
* PDF Generator (like jsPDF)

---

## 📂 Project Structure

```
invoice_generation_system/
│
├── client/              # React Frontend
│   ├── src/
│   └── public/
│
├── server/              # Node.js Backend
│   ├── routes/
│   ├── models/
│   └── controllers/
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/invoice_generation_system.git
cd invoice_generation_system
```

### 2️⃣ Setup Backend

```
cd server
npm install
npm start
```

### 3️⃣ Setup Frontend

```
cd client
npm install
npm start
```

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint  | Description        |
| ------ | --------- | ------------------ |
| GET    | /items    | Fetch all items    |
| POST   | /items    | Add new item       |
| GET    | /invoices | Fetch invoices     |
| POST   | /invoices | Create new invoice |

---

## 📄 Invoice Sample Includes

* Invoice Number & Date
* Customer Details
* Item List (Name, Quantity, Price)
* Tax Calculation
* Total Amount

---

## 🎯 Future Enhancements

* User authentication (Login/Register)
* Email invoice to customers
* Payment integration
* Dashboard analytics



---
