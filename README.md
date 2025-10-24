🛍️ Trend🍊ra eCommerce: Full-Stack MERN E-Shop 🛍️

Project Overview

Trendora eCommerce is a modern, full-stack e-commerce platform designed to deliver a fast, intuitive, and feature-rich shopping experience. Built using the robust MERN stack, the application emphasizes responsive design, seamless navigation, and a dedicated administrative interface for product and user management.

The entire frontend is built with React and styled using Tailwind CSS, ensuring a modular, maintainable, and highly responsive user interface that looks great on all devices.

Key Features

🛒 User Experience & Core Functionality

Intuitive Product Browsing: View categorized products with search, filtering, and sorting options.

Shopping Cart Management: Easily add, update, and remove items before checkout.

User Authentication (Auth): Secure sign-up, login, and protected routing.

Personalized Profile Page: Users can manage their personal details and view their order history.

💻 Admin Panel

Product Management: CRUD operations (Create, Read, Update, Delete) for all products.

Order Tracking: View and manage customer orders, updating status in real-time.

User Management: Overview and administration of registered users.

📱 Performance & Design

Fully Responsive Layout: Optimized for mobile, tablet, and desktop viewports using Tailwind CSS utilities.

Fast Development Cycle: Utilizes Vite for rapid tooling and build performance.

Efficient Deployment: Frontend seamlessly hosted on Vercel.

Technologies Used

Trendora is a MERN stack application, utilizing a modern, component-based approach for the frontend.

Category

Technology

Description

Frontend

React (Vite)

Main UI library for component-based architecture.



Tailwind CSS

Utility-first CSS framework for rapid and responsive styling.



React Router

Client-side routing for seamless page transitions.

Backend

Node.js (Express)

Fast, unopinionated web framework for the server.



MongoDB

NoSQL database for flexible and scalable data storage.



JWT

Token-based authentication for secure API access.

Project Screenshots

The following images highlight the design and functionality of the application across different platforms.

Desktop View

Home Page showcasing featured products:

Product Listing and Filters:

Detailed Product Page:

Shopping Cart View:

User Profile Dashboard:

Mobile Responsiveness 📱

Mobile Navigation and Homepage:

Mobile Product Listing:

Mobile Checkout/Cart:

Admin Panel 💻

Admin Dashboard Overview:

Admin Product Management Interface:

Admin User Management Interface:

Local Setup & Installation

To run the Trendora eCommerce project on your local machine, follow these steps.

Prerequisites

Node.js (v18+)

npm or yarn

MongoDB instance (local or Atlas)

1. Backend Setup

Clone the repository:

git clone [YOUR_REPO_URL]
cd trendora-ecommerce


Navigate to the backend directory and install dependencies:

cd backend
npm install


Configure Environment Variables:
Create a file named .env in the backend directory and add your configurations:

PORT=5000
MONGO_URI="YOUR_MONGODB_CONNECTION_STRING"
JWT_SECRET="YOUR_SECRET_KEY"
# Other necessary variables (e.g., payment gateway keys)


Run the server:

npm start


The server will start on http://localhost:5000.

2. Frontend Setup

Navigate to the frontend directory and install dependencies:

cd ../frontend
npm install


Configure API Endpoint:
Create a file named .env in the frontend directory and define your backend URL:

VITE_API_URL="http://localhost:5000/api"


Start the React development server:

npm run dev


The frontend application will be available at the address shown in your console (e.g., http://localhost:5173).

Deployment

The frontend application is deployed on Vercel, demonstrating efficient continuous deployment workflows. The backend API is typically deployed to a cloud hosting service (e.g., Render, AWS EC2) and connected to a remote MongoDB instance (e.g., MongoDB Atlas).
