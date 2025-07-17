# 🍽️ Restron - Multi-Vendor Restaurant Food Ordering Platform

**Restron** is a modern, multi-vendor food ordering and listing platform built with the powerful MERN stack (MongoDB, Express.js, Node.js, EJS, and Mongoose). It’s designed to help restaurants register, showcase dishes, and take customer orders with real-time validation, automated order cleanup, and a user-friendly interface.

---

## 🌟 Features

### 👥 Authentication & Authorization
- Secure registration and login system for both guests and vendors.
- Session-based authentication using `express-session`.

### 🏪 Vendor Functionality
- Vendors can register and create their own restaurant profile.
- Add, edit, and delete dishes (each with image upload using Cloudinary).
- View food orders placed by guests.

### 🍽️ Guest Functionality
- Browse restaurants and dishes with dynamic search and filters.
- Place an order with address validation (serving area check).
- Track booked vendors and order history.
- Add vendors to favourites.

### 💡 Core Logic
- ✅ Orders expire and auto-delete after 24 hours using MongoDB TTL (`expireAt`).
- ✅ Real-time address check on the frontend — users can only place orders if their address partially matches the vendor's service location.
- ✅ Average rating system across all vendor dishes.
- ✅ PDF menus and dish images hosted on Cloudinary.

### 🎨 UI Highlights
- Responsive and attractive EJS-based frontend.
- Search bar with auto-suggestion.
- Stunning success page and booking interface.
- Beautiful vendor cards with average pricing, rating stars, and order buttons.

---

## 🛠️ Tech Stack

| Technology | Role |
|-----------|------|
| **MongoDB** | Database for user, vendor, and order management |
| **Express.js** | Server-side framework |
| **Node.js** | Backend runtime |
| **EJS** | Frontend templating engine |
| **Mongoose** | ODM for MongoDB |
| **Cloudinary** | Image and PDF uploads |
| **Bootstrap / Custom CSS** | UI/UX styling |
| **JavaScript** | Frontend interactivity |

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/restron.git
   cd restron



   npm install


   MONGODB_URI=your_mongo_uri
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SESSION_SECRET=your_secret


http://localhost:3407