# ecommerce-website
🛒 An AI-powered e-commerce website with product recommendations. Users can upload or click on an image, and the system suggests visually similar products using image recognition.
🛍️ E-Commerce Frontend (React + React Router)

This is the frontend of a multi-user e-commerce platform built with React and React Router. It provides a seamless user experience for browsing products, managing shopping carts, handling authentication, and supporting AI-powered product recommendations.

✨ Features

🚀 Built with React + Vite for fast performance

🔀 React Router for multi-page navigation (Home, Products, Cart, Login, etc.)

👤 Supports multiple user roles (customers, admins)

🛒 Product listing, cart, and checkout pages

🔑 Authentication routes for login and user management

📷 AI-powered product recommendations via image upload and click-based discovery

🎨 Responsive UI ready for backend API integration

📂 Project Structure
ecommerce-frontend/
│── public/                # Static assets (favicon, images, etc.)
│── src/
│   ├── assets/            # Images, icons, styles
│   ├── components/        # Reusable UI components
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── ProductCard.jsx
│   │   └── ...
│   ├── layouts/           # Shared layouts for roles
│   │   ├── CustomerLayout.jsx
│   │   ├── AdminLayout.jsx
│   │   └── AuthLayout.jsx
│   ├── pages/             # Page-level components (grouped by role)
│   │   ├── customer/
│   │   │   ├── Home.jsx
│   │   │   ├── Products.jsx
│   │   │   ├── Cart.jsx
│   │   │   └── Profile.jsx
│   │   ├── admin/
│   │   │   ├── Dashboard.jsx
│   │   │   ├── ManageProducts.jsx
│   │   │   ├── Orders.jsx
│   │   │   └── Users.jsx
│   │   ├── auth/
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   └── ForgotPassword.jsx
│   │   └── common/
│   │       └── NotFound.jsx
│   ├── routes/            # Route definitions & protected routes
│   │   ├── CustomerRoutes.jsx
│   │   ├── AdminRoutes.jsx
│   │   └── AuthRoutes.jsx
│   ├── context/           # Context API (AuthContext, CartContext, etc.)
│   │   ├── AuthContext.jsx
│   │   └── CartContext.jsx
│   ├── services/          # API calls to Django backend
│   │   ├── authService.js
│   │   ├── productService.js
│   │   └── orderService.js
│   ├── utils/             # Helpers (formatting, validators, constants)
│   │   ├── validators.js
│   │   └── constants.js
│   ├── App.jsx            # Main app with routes
│   ├── main.jsx           # Entry point
│   └── index.css          # Global styles
│
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
