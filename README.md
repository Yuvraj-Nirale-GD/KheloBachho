# KheloBachho 🎮

**A Gaming E-Commerce Web Application Built with React**

KheloBachho is a frontend-based gaming e-commerce web application that allows users to explore games across different platforms, view product information, manage their shopping cart, and experience a demo checkout process.

The application is built using React and Vite, with React Router for navigation and Context API for global cart state management.

---

## ✨ Features

### 1. Home Page
- Gaming-themed landing page.
- Featured games and product categories.
- Navigation to different sections of the application.

### 2. Product Browsing
- Browse games across Mobile, PC, and PlayStation categories.
- Search products by name.
- Filter products by category and price.
- Sort products according to available sorting options.

### 3. Product Details
- View individual product information.
- Display product descriptions, prices, ratings, and other details.
- Add products to the shopping cart.

### 4. Shopping Cart
- Add and remove products.
- Increase or decrease product quantities.
- Calculate subtotal dynamically.
- Persist cart data using LocalStorage.

### 5. Checkout
- Guest checkout without requiring user registration.
- Shipping information form with input validation.
- Cash on Delivery and simulated online payment options.
- Order confirmation after successful form submission.

### 6. Order Confirmation
- Display order details.
- Show the selected payment method and payment status.

### 7. User Interface
- Dark gaming-themed interface.
- Responsive layout.
- Reusable React components.
- Toast notifications for user feedback.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React | Building the user interface |
| JavaScript | Application logic |
| Vite | Development server and build tool |
| React Router DOM | Client-side navigation |
| Context API | Global cart state management |
| HTML5 | Application structure |
| CSS3 | Styling and responsive design |
| LocalStorage | Cart persistence |
| sessionStorage | Temporary order information |
| Git & GitHub | Version control and source code hosting |

---

## 📁 Project Structure

```text
KheloBachho/
│
├── public/
│   └── images/
│
├── src/
│   ├── components/
│   │   ├── Footer.jsx
│   │   ├── Navbar.jsx
│   │   ├── ProductCard.jsx
│   │   └── Toast.jsx
│   │
│   ├── context/
│   │   └── CartContext.jsx
│   │
│   ├── data/
│   │   └── products.js
│   │
│   ├── pages/
│   │   ├── Cart.jsx
│   │   ├── Checkout.jsx
│   │   ├── Home.jsx
│   │   ├── NotFound.jsx
│   │   ├── OrderConfirmation.jsx
│   │   ├── ProductDetails.jsx
│   │   └── Products.jsx
│   │
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── .gitignore
└── README.md
```

---

## 🚀 Installation and Setup

Follow these steps to run the project locally.

### Prerequisites

- Node.js
- npm
- Git (optional)

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/KheloBachho.git
```

### Step 2: Navigate to the Project Directory

```bash
cd KheloBachho
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal to access the application.

### Step 5: Create a Production Build

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 💳 Checkout and Payment Behaviour

KheloBachho currently provides a frontend demonstration of the checkout process.

- Cash on Delivery is available for physical products.
- Online Payment is simulated for demonstration purposes.
- No actual payment gateway is integrated.
- No real financial transaction takes place.
- Order information is stored temporarily in sessionStorage.

**Note:** Digital products can be browsed and added to the cart, but the current cart flow restricts checkout when digital products are present.

---

## ⚠️ Project Limitations

This project is currently a frontend demonstration and does not include:

- Backend server or API integration.
- Database connectivity.
- User authentication and registration.
- Real payment gateway integration.
- Live inventory management.
- Actual digital product delivery or downloads.
- Permanent order history.

Product information is maintained using locally defined sample data.

---

## 🎯 Project Objective

The primary objective of KheloBachho is to understand and implement core React concepts through a practical e-commerce application.

The project demonstrates component-based architecture, state management, routing, form handling, browser storage, and frontend application development.

---

## 🔮 Future Improvements

Potential improvements include:

- Backend integration using Node.js and Express.
- Database integration using MongoDB or MySQL.
- User authentication and authorization.
- Real payment gateway integration.
- Wishlist functionality.
- Admin dashboard for product management.
- Order history and tracking.
- Actual digital product delivery.
- Improved testing and error handling.

---

## 👨‍💻 Developer


GitHub: https://github.com/Yuvraj-Nirale-GD

---
