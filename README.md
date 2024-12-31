# Crave Cart
Welcome to Crave Cart, your ultimate destination for seamless online food ordering. Built using the powerful MERN Stack, Crave Cart provides a user-friendly platform that connects food lovers with their favorite dishes, anytime, anywhere.
<br/>
<br/>

## Table Of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Tech Stack](#tech-stack)
- [Contributing](#contributing)
<br/>

## Introduction

Crave Cart is a powerful and user-friendly food delivery platform designed to enhance the online food ordering experience. Built using the MERN Stack, it allows users to browse menus, add items to their cart, place orders, and securely pay using Stripe. Admins can efficiently manage products and orders. Featuring role-based authentication, real-time updates, and beautiful alerts, Crave Cart ensures a smooth and enjoyable experience for users and admins alike.
<br/>
<br />

## Features
1. ***User Panel:***
   - A sleek, interactive interface for browsing restaurants, viewing products, and placing orders.
   - Includes features like login/signup, cart management, and order tracking.
   - Technologies: React.js, Redux, CSS, and JavaScript.
2. ***Admin Panel:***
   - Tools for managing products, orders, and users with role-based access.
   - Allows admins to monitor and process orders efficiently.
   - Technologies: React.js, Node.js, and MongoDB.
3. ***Authentication:***
   - Secure JWT-based authentication for login, signup, and user sessions.
   - Password hashing using Bcrypt ensures user security.
4. ***Payment Integration:***
   - Seamless integration with Stripe for secure and reliable payments.
5. ***Cart Management:***
   - Users can add or remove items from their cart and proceed to checkout.
6. ***Order Management:***
   - Users can view and track their order history.
   - Admins can update the status of customer orders in real time.
7. ***Product Filtering:***
   - Dynamic filters for users to sort food items by category, price, or availability.
8. ***Responsive Design:***
   - Fully responsive design ensures accessibility on mobile, tablet, and desktop devices.
9. ***Beautiful Alerts:***
   - Interactive alerts and modals enhance the user experience with meaningful feedback.
<br />

## Installation

1. **Clone the repository:**
     
     ```
     https://github.com/dharuv26/Crave-Cart.git
     ```
2. **Navigate to the project directory:**
     
     ```
     cd Crave-Cart
     ```
3. **Install Dependencies:**

   Frontend:
   ```
   cd frontend
   npm install
   ```
   Admin Panel:
   ```
   cd admin
   npm install
   ```
   Backend:
   ```
   cd backend
   npm install
   ```
4. **Setup environment variables:**
   Create a `.env` file in the `backend` directory with the following variables:
   ```
   JWT_SECRET=YOUR_SECRET_TEXT
   SALT=YOUR_SALT_VALUE
   MONGO_URL=YOUR_DATABASE_URL
   STRIPE_SECRET_KEY=YOUR_STRIPE_KEY
   ```
5. ***Setup the Frontend and Backend URL:***
    - App.jsx in Admin folder
        const url = YOUR_BACKEND_URL
     
    - StoreContext.js in Frontend folder
        const url = YOUR_BACKEND_URL
  
    - orderController in Backend folder
        const frontend_url = YOUR_FRONTEND_URL
6. ***Start the servers:***
    Frontend:
   ```
   npm start
   ```
   Admin Panel:
   ```
   npm start
   ```
   Backend:
   ```
   nodemon server.js
   ```
<br />

## Tech Stack
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en)
* [Express.js](https://expressjs.com/)
* [Mongodb](https://www.mongodb.com/)
* [Stripe](https://stripe.com/)
* [JWT-Authentication](https://jwt.io/introduction)
* [Multer](https://www.npmjs.com/package/multer)

## Contributing

  Contributions are welcome! If you'd like to contribute to this project, please follow these     guidelines:

  1. Fork the repository.
  2. Create a new branch: ```git checkout -b feature/your-feature-name```.
  3. Make your changes and commit them: ```git commit -m 'New:Add some feature'```.
  4. Push to the branch: ```git push origin feature/your-feature-name```.
  5. Open a pull request to the `main` branch of this repository.
<br/>