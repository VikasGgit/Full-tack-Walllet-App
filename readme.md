# Wallet App and Admin Panel

This repository contains the backend, admin panel, and mobile wallet app for a fully functional wallet management system. Below is an overview of the application and instructions on how to use it.

---

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [Login Credentials](#login-credentials)
- [How It Works](#how-it-works)
- [Usage Instructions](#usage-instructions)

---

## Overview

The Wallet Management System is composed of the following components:

1. **Admin Panel**: Built with Next.js, the admin panel allows administrators to manage users and wallet activities.
2. **Wallet App**: A React Native application (built with Expo) for users to manage their wallet, transactions, and account information.
3. **Backend API**: A Node.js and Express.js backend that handles all the core functionalities. MongoDB is used as the database, and Prisma ORM is employed for database operations.

---

## Technologies Used

- **Frontend**:
  - Admin Panel: Next.js
  - Wallet App: React Native (Expo framework)
- **Backend**:
  - Node.js with Express.js
  - MongoDB with Prisma ORM
- **Authentication**:
  - JSON Web Tokens (JWT)
- **Styling**:
  - Tailwind CSS (Admin Panel)
  - React Native styling (Wallet App)

---

## Features

### Admin Panel
- Manage user accounts (reset passwords, freeze/unfreeze accounts).
- View user transaction history.
- Logout functionality for admin.

### Wallet App
- User login and authentication.
- Wallet balance and transaction management.
- Intuitive interface for wallet activities.

### Backend API
- Handles all core functionalities, including user authentication, account management, and transaction processing.
- RESTful endpoints with secured access.

---

## Installation and Setup

### Backend (Node.js and Express.js)
1. Clone the repository.
2. Navigate to the backend directory.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up your `.env` file with MongoDB and Jwt credentials.
5. Run the backend:
   ```bash
   npm start
   ```

### Admin Panel (Next.js)
1. Navigate to the admin panel directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Access the admin panel at `http://localhost:3000`.

### Wallet App (React Native Expo)
1. Navigate to the wallet app directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Expo server:
   ```bash
   npm start
   ```
4. Scan the QR code using the Expo Go app to run the app on a physical device.

---

## Login Credentials

### Admin Login
- **Email**: `admin1@gmail.com`
- **Password**: `Admin123`

### User Login
- **Email**: `user1@gmail.com`
- **Password**: `User123`

---

## How It Works

1. **Admin Panel**:
   - Admin logs in using the credentials.
   - Admin can view and manage user accounts.
   - Reset user passwords or freeze/unfreeze accounts.
   - Logout when finished.

2. **Wallet App**:
   - Users log in using their credentials.
   - Users can view wallet balance, transaction history, and perform wallet-related operations.

3. **Backend**:
   - Handles API requests for both admin panel and wallet app.
   - Secures data using authentication and validation layers.

---

## Usage Instructions

1. Clone the repository.
2. Set up the backend by configuring the `.env` file with MongoDB credentials.
3. Run the backend, admin panel, and wallet app.
4. Use the login credentials provided above to explore both the admin panel and wallet app.

Feel free to contact me if you have questions or need further assistance!

