# 🌍 WanderLust

A full-stack **Airbnb-inspired accommodation booking platform** built with **Node.js, Express.js, MongoDB, and EJS**. WanderLust allows users to explore, create, manage, and review property listings through a clean and responsive interface.

> **Disclaimer:** This project is developed for educational purposes only and is inspired by Airbnb.

---

## 🚀 Features

### 👤 Authentication & Authorization
- User Registration & Login
- Secure Password Hashing
- Session-based Authentication
- Authorization for Listings and Reviews

### 🏠 Property Listings
- Create new listings
- View all available listings
- Update listing details
- Delete listings
- Property images
- Location & pricing details

### ⭐ Reviews
- Add reviews and ratings
- Delete reviews
- View customer feedback

### 📍 Location Support
- Display property location
- Map integration using Mapbox

### ☁️ Image Upload
- Upload property images
- Cloud image storage using Cloudinary

### ⚠️ Error Handling
- Custom Express Error Handler
- Async Error Wrapper
- User-friendly error pages

### 📱 Responsive UI
- Mobile-friendly design
- Bootstrap-based interface

---

# 🛠️ Tech Stack

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## Frontend
- EJS
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

## Authentication
- Passport.js
- Passport Local
- Express Session

## Cloud Services
- Cloudinary
- Multer
- Mapbox API

## Validation & Utilities
- Joi Validation
- Method Override
- Connect Flash

---

# 📂 Project Structure

```
WanderLust/
│
├── init/
│
├── models/
│
├── public/
│   ├── css/
│   └── js/
│
├── utils/
│   ├── expressError.js
│   └── wrapAsync.js
│
├── views/
│   ├── includes/
│   │   ├── navbar.ejs
│   │   └── footer.ejs
│   │
│   ├── layouts/
│   │   └── boilerplate.ejs
│   │
│   ├── listings/
│   │   ├── index.ejs
│   │   ├── new.ejs
│   │   ├── edit.ejs
│   │   └── show.ejs
│   │
│   └── error.ejs
│
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/WanderLust.git
```

```bash
cd WanderLust
```

---

## Install Dependencies

```bash
npm install
```

---

## Configure Environment Variables

Create a **.env** file in the project root.

```env
ATLASDB_URL=your_mongodb_connection_string

SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

MAP_TOKEN=your_mapbox_access_token
```

---

## Start the Server

```bash
node app.js
```

or (if using nodemon)

```bash
nodemon app.js
```

The application will be available at:

```
http://localhost:8080
```

---

# 📷 Screenshots

Add screenshots inside a **screenshots/** folder.

```
screenshots/
│
├── home.png
├── listing-details.png
├── add-listing.png
├── login.png
├── signup.png
└── review.png
```

---

# 📌 Main Functionalities

- User Authentication
- Authorization
- CRUD Operations for Listings
- Property Reviews
- Image Upload
- Interactive Maps
- Flash Messages
- Error Handling
- Responsive Layout
- MVC Architecture

---

# 🏗️ Architecture

```
Client (Browser)
        │
        ▼
Express.js Server
        │
 ┌──────┴───────┐
 │              │
 ▼              ▼
Views (EJS)   Controllers
        │
        ▼
     Models
        │
        ▼
MongoDB Database
```

---

# 🌟 Future Improvements

- Wishlist Feature
- Online Payments
- Booking Calendar
- Email Notifications
- Google OAuth Login
- Property Search Filters
- Chat between Host & Guest
- Admin Dashboard
- Property Availability Management
- Recommendation System

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📚 Learning Objectives

This project helped in understanding:

- Express.js Routing
- MongoDB CRUD Operations
- Mongoose ODM
- Authentication & Authorization
- MVC Architecture
- RESTful APIs
- Session Management
- Error Handling
- Image Upload
- Cloud Storage Integration

---

# 📄 License

This project is developed for educational purposes only and is not affiliated with Airbnb.

---

# 👨‍💻 Author

**Suraj Prajapati**

- GitHub: https://github.com/your-github-username
- LinkedIn: https://linkedin.com/in/your-linkedin-profile

---

## ⭐ If you like this project, don't forget to give it a Star!