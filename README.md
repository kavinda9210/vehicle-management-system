# 🚗 Vehicle Management System

This is a full-stack Vehicle Management System built with:

- **Frontend:** React.js  
- **Backend:** Laravel (REST API)  
- **Database:** MySQL  

The project is structured with both frontend and backend in the same repository:

```
vehicle-management-system/
├── Frontend/     # React application
└── Backend/      # Laravel REST API
```

---

## 🎥 Demo

Watch the full demo here:  
📺 [Click to watch on YouTube]()

You can also embed it directly:

[![Vehicle Management System Demo](https://youtu.be/9w3SjgjZVQU?si=tjYtng_Y2G_iP-Hh)](https://youtu.be/9w3SjgjZVQU?si=tjYtng_Y2G_iP-Hh)

---

## 🚀 Getting Started

### 🧰 Prerequisites

Make sure you have the following installed:

- Node.js & npm  
- PHP >= 8.x  
- Composer  
- MySQL  
- Laravel CLI  
- Git  

---

## 📁 Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/kavinda9210/vehicle-management-system.git
cd vehicle-management-system
```

---

### 2. Backend Setup (Laravel)

```bash
cd Backend

# Install PHP dependencies
composer install

# Copy .env file and configure
cp .env.example .env

# Generate application key
php artisan key:generate
```

Update the `.env` file with your database credentials:

```
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Then run:

```bash
# Run database migrations
php artisan migrate

# Serve the Laravel backend
php artisan serve
```

The backend will be available at `http://127.0.0.1:8000`.

---

### 3. Frontend Setup (React)

```bash
cd ../Frontend

# Install Node dependencies
npm install

# Start the React development server
npm start
```

The frontend will be available at `http://localhost:3000`.

---

## 🔗 API Integration

Make sure your React app is calling the correct Laravel API endpoint  
(e.g., `http://127.0.0.1:8000/api/vehicles`).

You can configure this in your React project using an `.env` file or your API service file.

---

## ✅ Features

- Add, update, and delete vehicles  
- View vehicle list and details  
- Fully integrated RESTful API  
- Responsive frontend UI  

---

## 📦 Deployment

For production deployment:

- Host the Laravel backend on a VPS, shared hosting, or services like Laravel Forge  
- Build the React frontend using `npm run build` and host it on Vercel, Netlify, or your own server  

---

## 👨‍💻 Author

**Kavinda**  
GitHub: [@kavinda9210](https://github.com/kavinda9210)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
