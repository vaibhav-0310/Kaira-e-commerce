# 👠 Kiara - E-Commerce Website

Kiara is a modern, stylish, and full-featured e-commerce website built with Node.js, Express, EJS, and MongoDB. It enables users to browse products, manage a shopping cart, register/login, and complete purchases. The admin panel allows for product and user management.

## 🚀 Features

* 🛍️ User-friendly product browsing
* 🛒 Cart and checkout system
* 🔐 User authentication (Register/Login/Logout)
* 🧑‍💼 Admin dashboard for managing products and users
* 📦 Order management system (if applicable)
* 💳 PayPal payment gateway integration
* 📸 Dynamic product rendering with EJS
* 🌐 Responsive frontend UI

## 🛠️ Tech Stack

* **Frontend:** EJS, HTML5, CSS3, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB with Mongoose
* **Authentication:** Express-Session / Passport.js (if used)
* **Templating Engine:** EJS
* **Payment Gateway:** PayPal

## ⚙️ Installation

1. Clone the repo

   ```bash
   https://github.com/vaibhav-0310/Kaira-e-commerce.git
   cd kiara
   ```
2. Install dependencies

   ```bash
   npm install
   ```
3. Set up environment variables
   Create a .env file in the root directory and add:

   ```env
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   SESSION_SECRET=your_secret
   PAYPAL_CLIENT_ID=your_paypal_client_id
   PAYPAL_CLIENT_SECRET=your_paypal_client_secret
   ```
4. Run the app

   ```bash
   npm start
   ```

## 🧠 Future Enhancements

* User profile management
* Wishlist functionality
* REST API version
