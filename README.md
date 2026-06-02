# EduCase Assignment – PopX Authentication UI

## 📌 Project Overview

This project is a frontend implementation of the **PopX Authentication Flow** developed as part of the EduCase assignment.

The application allows users to:

* Create a new account
* Login using registered credentials
* View account information after successful login

User data is stored in **Local Storage** to simulate authentication without requiring a backend.

---

## 🚀 Features

### Landing Page

* Welcome screen
* Navigate to:

  * Create Account
  * Sign In

### Create Account Page

* User registration form
* Required field validation
* Stores user details in Local Storage
* Redirects to Sign In page after successful registration

### Sign In Page

* Login using registered email and password
* Credential validation
* Error handling for invalid credentials
* Redirects to Account page on successful login

### Account Page

* Displays registered user information
* Reads user data from Local Storage
* Responsive profile layout

---

## 🛠️ Tech Stack

* React 19
* React Router DOM
* Tailwind CSS
* Vite

---

## 📂 Project Structure

```bash
src/
│
├── pages/
│   ├── Landing.jsx
│   ├── CreateAccount.jsx
│   ├── Signin.jsx
│   └── Account.jsx
│
├── constants.js
├── App.jsx
└── main.jsx
```

---

## ⚙️ Installation & Setup

### Clone the repository

```bash
git clone <repository-url>
```

### Navigate to project folder

```bash
cd educase-assignment
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

---

## 📋 Validation Rules

### Create Account

Required Fields:

* Full Name
* Phone Number
* Email Address
* Password

Validation:

* Full Name cannot be empty
* Phone Number must contain at least 10 digits
* Email Address is required
* Password is required

---

## 🔐 Authentication Flow

1. User creates an account.
2. Data is stored in browser Local Storage.
3. User logs in using registered credentials.
4. Credentials are verified against stored data.
5. On successful login, user is redirected to the Account page.

---

## 📱 Responsive Design

The application is designed to be mobile-friendly and closely follows the provided PopX UI design.

---

## 🔮 Future Improvements

* Backend integration
* JWT Authentication
* Protected Routes
* Password Encryption
* Form validation using React Hook Form + Zod
* Global State Management
* User Profile Editing
* Logout Functionality

---

## 👨‍💻 Author

**Vivek Jadhav**

Frontend Developer

Tech Stack:

* HTML
* CSS
* JavaScript
* React.js
* Tailwind CSS
* Git & GitHub

```
```
