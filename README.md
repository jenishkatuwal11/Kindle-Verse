# KindleVerse 📚

**KindleVerse** is a full-stack bookstore web application that allows users to explore, search, and purchase books online while enabling admins to manage the entire catalog through a powerful backend system.

---

## 🌟 Features

### 🔒 Authentication
- User registration and login
- Email verification via OTP
- Password reset with OTP

### 🛍️ User Functionality
- Browse books by genre, language, and format
- Wishlist (bookmark) books
- Add books to cart
- Place orders and view order history
- Apply promo codes for discounts
- View and update profile

### 🛠️ Admin Functionality
- Add, edit, and delete books
- Mark books as "On Sale"
- Manage fields: genre, publication, language, format, and offer price date
- Secure admin login with password reset
- View and manage all orders

---

## 🧱 Tech Stack

### 🔹 Frontend
- React (with Vite)
- Tailwind CSS (latest)
- Axios for API requests

### 🔹 Backend
- ASP.NET Core Web API
- Entity Framework Core (EF Core)
- PostgreSQL database
- ASP.NET Identity for authentication
- Swagger for API documentation

---

## 📁 Folder Structure

KindleVerse/
├── Controllers/
├── Models/
├── DTOs/
├── Data/
├── Migrations/
├── Program.cs
├── appsettings.json
└── ...

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/jenishkatuwal11/Kindle-Verse.git
cd Kindle-Verse

##  Set up the database
--> Ensure PostgreSQL is installed and running
--> Update the connection string in appsettings.json

## Run the backend

dotnet ef database update
dotnet run

## Frontend setup
The frontend is built using Vite + React + Tailwind CSS (located in the pages folder):

cd folder name
npm install
npm run dev

## Contributing
Contributions are welcome!
Feel free to fork the project and submit a pull request.

## 📧 Contact
Created by Jenish Katuwal
📬 Email: jenishkatuwal7@gmail.com

---

Let me know if you want to add badges, deployment instructions, or screenshots — I can update the README accordingly.
