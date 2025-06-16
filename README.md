# E-commerce Web App

This is a full-stack E-commerce web application built with React (Vite), Node.js, Express, and MongoDB. It features user authentication, product management, cart, order placement, admin dashboard, and payment integration (Stripe & Razorpay).

## Features
- User registration and login
- Product listing and details
- Add to cart and checkout
- Multiple payment methods: Cash on Delivery, Stripe, Razorpay
- Order history and tracking
- Admin panel for managing products and orders
- Responsive UI with Tailwind CSS

## Tech Stack
- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Payments:** Stripe, Razorpay
- **Cloudinary** for image uploads

## Getting Started

### Prerequisites
- Node.js & npm
- MongoDB Atlas account (or local MongoDB)
- Stripe & Razorpay accounts for payment integration

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/charugupta615/E-commerce-Web-App.git
   cd E-commerce-Web-App
   ```
2. **Install dependencies:**
   - For backend:
     ```bash
     cd backend
     npm install
     ```
   - For frontend:
     ```bash
     cd ../frontend
     npm install
     ```
   - For admin panel:
     ```bash
     cd ../admin
     npm install
     ```
3. **Set up environment variables:**
   - Copy `.env.example` to `.env` in each folder and fill in your credentials (MongoDB URI, Stripe, Razorpay, Cloudinary, etc).

### Running the App
- **Backend:**
  ```bash
  cd backend
  npm start
  ```
- **Frontend:**
  ```bash
  cd frontend
  npm run dev
  ```
- **Admin Panel:**
  ```bash
  cd admin
  npm run dev
  ```

## Folder Structure
```
full_stack/
  backend/    # Express API
  frontend/   # User-facing React app
  admin/      # Admin dashboard React app
```

## Deployment
- You can deploy the backend to platforms like Vercel, Heroku, or Render.
- Frontend and admin can be deployed to Vercel, Netlify, or similar.

## License
This project is for educational purposes. Feel free to use and modify it.

---
**Made with ❤️ by charugupta615**
