# 🍔 Zepto Food

<p align="center">
  <strong>Full-Stack Food Delivery Web Application</strong>
</p>

<p align="center">
  A modern food ordering platform built with React, TypeScript, Node.js, Express.js and MySQL.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React%20%7C%20TypeScript-blue" alt="Frontend" />
  <img src="https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-green" alt="Backend" />
  <img src="https://img.shields.io/badge/Database-MySQL-orange" alt="Database" />
  <img src="https://img.shields.io/badge/ORM-Sequelize-red" alt="Sequelize" />
  <img src="https://img.shields.io/badge/Build-Vite-purple" alt="Vite" />
  <img src="https://img.shields.io/badge/Styling-Tailwind%20CSS-38BDF8" alt="Tailwind CSS" />
</p>

---

## 📌 Overview

**Zepto Food** is a full-stack food delivery web application designed to provide a smooth online food ordering experience.

The application follows a separate frontend and backend architecture. The frontend is built with React and TypeScript, while the backend provides REST APIs using Node.js and Express.js. MySQL is used for persistent data storage with Sequelize ORM.

The project demonstrates practical implementation of:

* Component-based frontend development
* REST API development
* Database integration
* CRUD operations
* Product management
* Category-based browsing
* Shopping cart management
* Checkout workflow
* State management using React Context
* Responsive UI development

---

## ✨ Key Features

### 👤 User Features

* User registration and sign-up
* User-friendly navigation
* Product browsing
* Category-based product discovery
* Product details
* Search functionality
* Add products to cart
* Update cart quantities
* Remove products from cart
* Checkout workflow

### 🛒 Shopping Experience

* Product cards
* Product detail pages
* Category pages
* Search results
* Cart management
* Checkout page
* Responsive layout

### ⚙️ Backend Features

* RESTful API architecture
* Express.js server
* MySQL database integration
* Sequelize ORM
* MVC-style project organization
* Controller-based business logic
* Route separation
* Database configuration
* CRUD operations

### 🎨 Frontend Features

* React + TypeScript
* Reusable components
* React Context API
* Responsive design
* Tailwind CSS
* Vite development environment
* Type-safe application structure

---

## 🛠️ Tech Stack

### Frontend

| Technology        | Purpose                   |
| ----------------- | ------------------------- |
| React.js          | UI development            |
| TypeScript        | Type-safe JavaScript      |
| Tailwind CSS      | Styling and responsive UI |
| Vite              | Frontend build tool       |
| React Context API | State management          |

### Backend

| Technology | Purpose                        |
| ---------- | ------------------------------ |
| Node.js    | JavaScript runtime             |
| Express.js | REST API framework             |
| Sequelize  | ORM                            |
| MySQL      | Relational database            |
| CORS       | Cross-origin API communication |

### Development Tools

| Tool    | Purpose                 |
| ------- | ----------------------- |
| Git     | Version control         |
| GitHub  | Source code hosting     |
| VS Code | Development environment |
| Postman | API testing             |

---

## 🏗️ Application Architecture

```text
                    ┌──────────────────────┐
                    │      User / Client   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   React Frontend     │
                    │   TypeScript + Vite  │
                    └──────────┬───────────┘
                               │
                         HTTP / REST API
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Express Backend    │
                    │      Node.js         │
                    └──────────┬───────────┘
                               │
                    ┌──────────┴───────────┐
                    ▼                      ▼
             ┌──────────────┐      ┌──────────────┐
             │ Controllers  │      │    Routes    │
             └──────┬───────┘      └──────┬───────┘
                    │                     │
                    └──────────┬──────────┘
                               ▼
                    ┌──────────────────────┐
                    │ Sequelize ORM        │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       MySQL          │
                    └──────────────────────┘
```

---
---

## 📸 Screenshots

### 🏠 Home & User Interface

<table>
  <tr>
    <td><img src="screenshots/1.png" width="450"/></td>
    <td><img src="screenshots/2.png" width="450"/></td>
  </tr>
  <tr>
    <td><img src="screenshots/3.png" width="450"/></td>
    <td><img src="screenshots/4.png" width="450"/></td>
  </tr>
</table>

### 🍔 Products & Categories

<table>
  <tr>
    <td><img src="screenshots/5.png" width="450"/></td>
    <td><img src="screenshots/6.png" width="450"/></td>
  </tr>
  <tr>
    <td><img src="screenshots/7.png" width="450"/></td>
    <td><img src="screenshots/8.png" width="450"/></td>
  </tr>
</table>

### 🔎 Product Details & Search

<table>
  <tr>
    <td><img src="screenshots/9.png" width="450"/></td>
    <td><img src="screenshots/10.png" width="450"/></td>
  </tr>
  <tr>
    <td><img src="screenshots/11.png" width="450"/></td>
    <td><img src="screenshots/12.png" width="450"/></td>
  </tr>
</table>

### 🛒 Cart & Authentication

<table>
  <tr>
    <td><img src="screenshots/cart.png" width="450"/></td>
    <td><img src="screenshots/signup.png" width="450"/></td>
  </tr>
</table>

---

## 📁 Project Structure

```text
Zepto-Food/
│
├── Backend/
│   │
│   ├── Controller/
│   │   ├── ProductController.js
│   │   ├── StudentController.js
│   │   └── UserController.js
│   │
│   ├── Models/
│   │   ├── ProductModel.js
│   │   ├── StudentModel.js
│   │   └── UserModel.js
│   │
│   ├── Routes/
│   │   ├── ProductRoutes.js
│   │   ├── StudentRoutes.js
│   │   └── UserRoutes.js
│   │
│   ├── config/
│   │   └── db.js
│   │
│   ├── index.js
│   ├── package.json
│   └── package-lock.json
│
├── Frontend/
│   │
│   ├── public/
│   │
│   ├── src/
│   │   │
│   │   ├── components/
│   │   │   ├── BannerCarousel.tsx
│   │   │   ├── CategoryCard.tsx
│   │   │   ├── Footer.tsx
│   │   │   ├── Header.tsx
│   │   │   ├── ProductCard.tsx
│   │   │   └── ProductRow.tsx
│   │   │
│   │   ├── context/
│   │   │   └── CartContext.tsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Cart.tsx
│   │   │   ├── CategoryPage.tsx
│   │   │   ├── Checkout.tsx
│   │   │   ├── Home.tsx
│   │   │   ├── NotFound.tsx
│   │   │   ├── ProductDetail.tsx
│   │   │   ├── Search.tsx
│   │   │   └── SignUp.tsx
│   │   │
│   │   ├── App.tsx
│   │   ├── data.ts
│   │   ├── index.css
│   │   ├── main.tsx
│   │   └── types.ts
│   │
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   └── vite.config.ts
│
├── .gitignore
├── package-lock.json
└── README.md
```

> `node_modules/` and generated build files are intentionally excluded from the documented source structure.

---

## 🔑 Important Modules

### Frontend

**Components**

* `Header.tsx` — application navigation
* `Footer.tsx` — application footer
* `BannerCarousel.tsx` — promotional/banner section
* `CategoryCard.tsx` — category presentation
* `ProductCard.tsx` — reusable product UI
* `ProductRow.tsx` — product listing row

**Pages**

* `Home.tsx` — home page
* `CategoryPage.tsx` — category-based products
* `ProductDetail.tsx` — product information
* `Search.tsx` — product search
* `Cart.tsx` — shopping cart
* `Checkout.tsx` — checkout workflow
* `SignUp.tsx` — user registration
* `NotFound.tsx` — 404 page

**State Management**

* `CartContext.tsx` — centralized cart state and cart operations

### Backend

**Controllers**

* `ProductController.js` — product-related business logic
* `UserController.js` — user-related operations
* `StudentController.js` — student-related controller

**Models**

* `ProductModel.js` — product database model
* `UserModel.js` — user database model
* `StudentModel.js` — student database model

**Routes**

* `ProductRoutes.js` — product API routes
* `UserRoutes.js` — user API routes
* `StudentRoutes.js` — student API routes

**Database**

* `config/db.js` — database connection/configuration

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/atulkumar-gupta/Zepto-Food.git
cd Zepto-Food
```

### 2. Backend Setup

```bash
cd Backend
npm install
```

Configure your database connection in:

```text
Backend/config/db.js
```

Start the backend:

```bash
npm run dev
```

For production/start mode:

```bash
npm start
```

### 3. Frontend Setup

Open a new terminal:

```bash
cd Frontend
npm install
```

Start the frontend:

```bash
npm run dev
```

The Vite development server will provide the local URL in the terminal.

---

## 🗄️ Database

The backend uses **MySQL** with **Sequelize ORM**.

Database configuration is handled through:

```text
Backend/config/db.js
```

The application uses Sequelize to interact with relational database models.

---

## 🔐 Environment Variables

Never commit real credentials, passwords, API keys or database secrets to GitHub.

If environment variables are required, create a local `.env` file and keep it excluded through `.gitignore`.

Example:

```env
DB_HOST=localhost
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=zepto_food
DB_PORT=3306
```

> Replace the values with your local/database configuration.

---

## 🧪 API Testing

Backend APIs can be tested using **Postman**.

Recommended API testing flow:

```text
Client
  ↓
HTTP Request
  ↓
Express Route
  ↓
Controller
  ↓
Sequelize Model
  ↓
MySQL
```

---

## 📈 Development Highlights

This project demonstrates practical full-stack development skills including:

* Frontend and backend separation
* REST API development
* React component architecture
* TypeScript development
* React Context API
* CRUD operations
* MySQL database integration
* Sequelize ORM
* Responsive UI development
* Reusable component design
* Git/GitHub workflow

---

## 🚀 Future Improvements

* JWT-based authentication
* Password hashing
* Online payment integration
* Order tracking
* Admin dashboard
* Product management panel
* Image upload
* Deployment with CI/CD
* Automated testing
* API documentation with Swagger

---

## 👨‍💻 Author

### Narendra Bisht

**MERN / Full Stack Developer**

* GitHub: https://github.com/Narendrabishts
* LinkedIn: https://www.linkedin.com/in/narendra-bisht-15b1321b9/
* Portfolio: 

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐.

**Repository:**
https://github.com/Narendrabishts/Zepto-Food-main
