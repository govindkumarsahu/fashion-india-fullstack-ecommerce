# Fashion India - Full Stack E-Commerce Platform

An end-to-end e-commerce application built with modern web technologies, featuring a user-friendly frontend, robust backend API, and an admin dashboard for product management. This project demonstrates full-stack development skills, including authentication, payment integration, cloud storage, and responsive UI design.

## 🚀 Features

- **User Authentication**: Secure login/signup with JWT tokens.
- **Product Catalog**: Browse, search, and filter products by category, subcategory, and size.
- **Shopping Cart & Checkout**: Add items to cart, place orders, and integrate with Razorpay/Stripe for payments.
- **Admin Panel**: Manage products, view orders, and handle inventory.
- **Responsive Design**: Optimized for desktop and mobile using TailwindCSS.
- **Cloud Integration**: Image uploads via Cloudinary, data storage with MongoDB Atlas.
- **Real-time Updates**: Hot reload during development with Vite and Nodemon.

## 🛠️ Tech Stack

### Frontend (User & Admin)
- **React**: Component-based UI library for dynamic interfaces.
- **Vite**: Fast build tool for modern web development.
- **TailwindCSS**: Utility-first CSS framework for responsive styling.
- **Axios**: HTTP client for API requests.
- **React Router**: Client-side routing for single-page applications.
- **React Toastify**: Notification system for user feedback.

### Backend
- **Node.js**: JavaScript runtime for server-side logic.
- **Express.js**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database with Mongoose ODM.
- **JWT**: JSON Web Tokens for secure authentication.
- **Bcrypt**: Password hashing for user security.
- **Multer**: Middleware for file uploads.
- **Cloudinary**: Cloud-based image storage and management.
- **Razorpay/Stripe**: Payment gateway integrations.

### Deployment & Tools
- **Vercel**: Serverless deployment for frontend and backend.
- **Git**: Version control.
- **Postman**: API testing.
- **ESLint**: Code linting for JavaScript.

## 📋 Prerequisites

- Node.js (v16+)
- MongoDB Atlas account (for cloud database)
- Cloudinary account (for image uploads)
- Razorpay/Stripe accounts (for payments)

## 🔧 Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/fashion-india.git
   cd fashion-india
   ```

2. **Backend Setup**:
   ```bash
   cd backend
   npm install
   ```
   - Create a `.env` file with your credentials (see `.env.example`).
   - Start the server: `npm run server`

3. **Frontend Setup**:
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

4. **Admin Panel Setup**:
   ```bash
   cd ../admin
   npm install
   npm run dev
   ```

5. **Environment Variables**:
   - Backend: `MONGODB_URI`, `JWT_SECRET`, `CLOUDINARY_*`, `STRIPE_SECRET_KEY`, `RAZORPAY_KEY_SECRET`
   - Frontend/Admin: `VITE_BACKEND_URL`

## 🎯 Usage

- **Local Development**: Run all three parts as above. Access at localhost:5173 (frontend), localhost:5174 (admin), localhost:4000 (backend).
- **API Endpoints**: See backend routes for user, product, cart, and order management.
- **Admin Login**: Use credentials from `.env` (e.g., email: admin@example.com, password: greatstack123).

## 🚀 Deployment

### Vercel Deployment
1. **Frontend/Admin**: Build with `npm run build`, deploy to Vercel, set `VITE_BACKEND_URL` to live backend URL.
2. **Backend**: Deploy `backend` folder to Vercel with environment variables in dashboard.

### Alternative Hosting
- Backend: Heroku, Railway, or Render.
- Database: MongoDB Atlas.
- Images: Cloudinary.

## 🤝 Contributing

Contributions welcome! Fork the repo, create a feature branch, and submit a PR. Follow ESLint rules and write tests where possible.

## 📄 License

This project is licensed under the ISC License.

## 📞 Contact

- **Developer**: [Your Name]
- **Email**: skgovind0904@gmail.com
- **LinkedIn/GitHub**: [Your Profiles]

---

*Built with passion for modern web development and e-commerce innovation. Perfect for showcasing full-stack skills in job applications!*
