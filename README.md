<h1 align="center">shop-Ease🛒</h1>

---

# 🚀 Shop-Ease: Full-Stack E-Commerce Web Application  

Shop-Ease is a modern and robust e-commerce web application built with the MERN stack. Designed for seamless shopping experiences, this platform integrates essential e-commerce functionalities, secure payment systems, and a user-friendly interface.  

---

## 🌟 Features  

### 🔐 Authentication & Authorization  
- User **Signup & Login** system.  
- Secure **JWT Authentication** with Access & Refresh tokens.  

### 🛒 E-Commerce Core  
- **Product Management**: Add, update, and view products.  
- **Category Management**: Organize products into categories.  
- **Shopping Cart**: Dynamic cart with quantity updates.  
- **Checkout Process**: Smooth and user-friendly flow.  
- **Coupon System**: Discounts via promo codes.  

### 💳 Payments  
- Integrated **Stripe Payment Gateway** for secure and fast transactions.  

### 👑 Admin Dashboard  
- Manage products, categories, and sales.  
- Access **Sales Analytics** for insights.  

### 🔧 Backend & Caching  
- **MongoDB** for database management.  
- **Redis Caching** for optimized performance and faster load times.  

### 🎨 Design & Frontend  
- Built with **React** and styled using **Tailwind CSS** for a modern, responsive design.  

---

## 💻 Tech Stack  

- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB, Redis  
- **Payments**: Stripe API  
- **Authentication**: JWT  
- **Version Control**: Git & GitHub  

---

## 📂 Project Structure  

```
Shop-Ease-App/  
├── client/  
│   ├── src/  
│   │   ├── components/  
│   │   ├── pages/  
│   │   └── utils/  
├── server/  
│   ├── config/  
│   ├── controllers/  
│   ├── models/  
│   ├── routes/  
│   └── middleware/  
└── README.md  
```  

---

## 🛠️ Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/chamath09/Shop-Ease-App.git  
   cd Shop-Ease-App  
   ```  

2. Install dependencies for both client and server:  
   ```bash  
   cd client  
   npm install  
   cd ../server  
   npm install  
   ```  

3. Set up environment variables:  
   Create a `.env` file in the `server` folder with the following:  
   ```env  
   MONGO_URI=your_mongo_connection_string  
   REDIS_HOST=your_redis_host  
   STRIPE_SECRET_KEY=your_stripe_secret_key  
   JWT_SECRET=your_jwt_secret  
   ```  

4. Run the application:  
   ```bash  
   # Run client and server concurrently  
   npm run dev  
   ```  

---

## 📹 Demo  

Check out the live demo of the app in action: [Link to Demo Video]  

---

## 📊 Screenshots  

### 1. Add New Product  
![Add New Product](./assets/images/add-product.jpg)  

### 2. Shopping Cart  
![Shopping Cart](./assets/images/shopping-cart.jpg)  

### 3. Admin Dashboard  
![Admin Dashboard](./assets/images/admin-dashboard.jpg)  

---

## 🤝 Contribution  

Contributions are welcome! Follow these steps:  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature/your-feature-name`.  
3. Commit your changes: `git commit -m 'Add some feature'`.  
4. Push to the branch: `git push origin feature/your-feature-name`.  
5. Open a pull request.  

---

## 📧 Contact  

Feel free to reach out for any questions or feedback!  
- **GitHub**: [chamath09](https://github.com/chamath09)  
- **Email**: chamath@example.com  

---

