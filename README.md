# ShopX - Full Stack E-Commerce Platform

A powerful and feature-rich e-commerce platform built with the MERN stack (MongoDB, Express, React, Node.js). This project demonstrates modern web development practices with a complete shopping experience including user authentication, product management, shopping cart, payment processing, and an admin dashboard.

## 🚀 Features

- **User Authentication & Authorization**
  - Secure user registration and login
  - JWT-based authentication using cookies
  - Password reset functionality
  - Role-based access control (Admin/User)

- **Product Management**
  - Browse products with advanced filtering and search
  - Product categories and pagination
  - Detailed product views with images
  - Product ratings and reviews system

- **Shopping Experience**
  - Add to cart functionality
  - Shopping cart management
  - Shipping information collection
  - Order confirmation and tracking

- **Payment Integration**
  - Stripe payment gateway integration
  - Secure checkout process
  - Order history and details

- **Admin Dashboard**
  - Complete product management (CRUD operations)
  - User management system
  - Order management and processing
  - Review moderation
  - Sales analytics and reporting

- **Additional Features**
  - Image upload using Cloudinary
  - Redux for state management
  - Responsive design
  - Real-time updates
  - Email notifications

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux (State Management)
- React Router
- Axios
- Bootstrap & Material-UI
- Stripe React
- SASS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT (JSON Web Tokens)
- Bcrypt.js
- Stripe
- Cloudinary
- Nodemailer

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Backend Setup

1. Navigate to the root directory
2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=5000
DB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
COOKIE_EXPIRE=7
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_API_KEY=your_stripe_api_key
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_EMAIL=your_email
SMTP_PASSWORD=your_email_password
SMTP_FROM_NAME=ShopX
```

4. Start the server:
```bash
npm start
```

### Frontend Setup

1. Navigate to the client directory:
```bash
cd client
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open at `http://localhost:3000`

## 🏗️ Project Structure

```
MERN-Stack-Full-Ecommerce-Site/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── actions/       # Redux actions
│       ├── components/    # Reusable components
│       ├── pages/         # Page components
│       ├── reducers/      # Redux reducers
│       └── store.js       # Redux store
├── config/                # Configuration files
├── controller/            # Route controllers
├── middleware/            # Custom middleware
├── models/                # Database models
├── routes/                # API routes
├── utils/                 # Utility functions
└── index.js              # Server entry point
```

## 📸 Screenshots

### Homepage
![Home Page](./assets/2022-08-03_094154.png)

### Product Page
![Product Page](./assets/2022-08-03_094255.png)

### Product Details
![Product Details](./assets/2022-08-03_094343.png)

### Shopping Cart
![Cart Page](./assets/2022-08-03_094443.png)

### Order Details
![Order Details](./assets/2022-08-03_094556.png)

## 🔐 Environment Variables

Make sure to set up all the required environment variables in the `.env` file for the application to work properly.

## 📝 License

This project is licensed under the ISC License.

## 👨‍💻 Author

**AYUSH**

## 🙏 Acknowledgments

- Built with modern web development best practices
- Uses industry-standard libraries and frameworks
- Follows RESTful API design principles
- Implements secure authentication and authorization

---

**Note:** Make sure to configure all environment variables and third-party services (MongoDB, Cloudinary, Stripe) before running the application.
