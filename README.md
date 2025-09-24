# Project README

## Shopo

Multi-Vendor E-Commerce Platform (MERN Stack)

## Overview

This repository contains a **Multi-Vendor E-Commerce Project** built using the **MERN stack** (MongoDB, Express.js, React, Node.js). The platform allows multiple vendors to register, manage their products, and sell to customers under a single marketplace. It includes core e-commerce features such as authentication, product listings, shopping cart, orders, payments, and admin/vendor dashboards.

The included screenshots illustrate UI screens, user flows, and key features.

## Tech Stack

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT-based authentication
* **Real-Time Updates (optional):** Socket.IO

## Key Features

* **Multi-Vendor Support:** Vendors can create accounts, add/update products, and manage sales.
* **Product Management:** Categories, search, filters, and product details.
* **Cart & Checkout:** Users can add items to the cart, apply discounts, and proceed with checkout.
* **Order Management:** Vendors can track orders and update order statuses.
* **Admin Dashboard:** Admin can manage vendors, users, and overall platform settings.
* **Responsive UI:** Works across devices (desktop, tablet, mobile).


## Project Bio

This project was created to demonstrate a **scalable, real-world e-commerce solution** using the MERN stack. It showcases:

* Designing for **multi-vendor workflows**.
* Building **secure and efficient backends** with Node.js & Express.
* Creating **modern, responsive UIs** with React & Tailwind.
* Managing **large datasets** in MongoDB.
* Handling **e-commerce-specific challenges** such as payments, carts, and orders.


## Screenshot Previews

Here are all screenshots displayed directly:

![Screenshot 2024-04-22 160830](Screenshot%202024-04-22%20160830.png)
![Screenshot 2024-04-22 161413](Screenshot%202024-04-22%20161413.png)
![Screenshot 2024-04-22 161722](Screenshot%202024-04-22%20161722.png)
![Screenshot 2024-04-22 161745](Screenshot%202024-04-22%20161745.png)
![Screenshot 2024-04-22 161915](Screenshot%202024-04-22%20161915.png)
![Screenshot 2024-04-22 162103](Screenshot%202024-04-22%20162103.png)
![Screenshot 2024-04-22 162126](Screenshot%202024-04-22%20162126.png)
![Screenshot 2024-04-22 162216](Screenshot%202024-04-22%20162216.png)
![Screenshot 2024-04-22 162313](Screenshot%202024-04-22%20162313.png)
![Screenshot 2024-04-22 162434](Screenshot%202024-04-22%20162434.png)
![Screenshot 2024-04-22 162534](Screenshot%202024-04-22%20162534.png)
![Screenshot 2024-04-22 162925](Screenshot%202024-04-22%20162925.png)




## Setup & Installation

### Prerequisites

- Node.js (v14 or above) and npm / Yarn installed
- MongoDB installed & running
- Git

## Steps to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/arjunshettyz/Shopo.git
cd Shopo

# 2. Install frontend dependencies
cd frontend
npm install
# or
yarn install

# 3. Install backend dependencies
cd ../backend
npm install
# or
yarn install

# 4. Configure environment variables
# Create a .env file in both frontend and backend (if applicable)
# Example:
# BACKEND_PORT=5000
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
# FRONTEND_URL=http://localhost:3000

# 5. Start the backend server
cd backend
npm run dev
# or
yarn dev

# 6. Start the frontend app
cd ../frontend
npm start
# or
yarn start

# 7. Access the app
# Open your browser and visit:
# http://localhost:3000
