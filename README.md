# CINIVERSE
# 🚗 AUTOHUB – Smart Car Showroom & Automotive Marketplace

AUTOHUB is a modern car showroom and automotive marketplace web application where users can explore, compare, and discover cars. It provides a platform for customers, showroom agents, and administrators to manage vehicle information and showroom activities.

## 🌟 Project Overview

AUTOHUB aims to make the car-buying experience easier by bringing vehicle information, comparisons, showroom services, and customer interactions into one platform.

## 🎯 Problem Statement

Traditional car showrooms often require customers to visit different locations to compare vehicles, check specifications, and enquire about prices.

AUTOHUB solves this problem by providing a centralized digital platform where users can explore vehicles and access showroom services online.

## ✨ Key Features

### 👤 Customer Features
- User registration and login
- Browse available cars
- Search cars by name and brand
- Filter cars by price, fuel type, transmission, and category
- View detailed car specifications
- Compare multiple vehicles
- Add cars to favourites or wishlist
- Submit enquiries
- Book test drives
- View booking history

### 🚘 Vehicle Management
- Add new vehicles
- Update vehicle details
- Delete vehicle listings
- Upload car images
- Manage new and used cars
- Display vehicle availability

### 🧮 Smart Tools
- EMI calculator
- Car comparison system
- Advanced search and filtering
- AI-powered car recommendation assistant (planned feature)

### 🛠️ Admin Features
- Admin login
- Manage users
- Manage vehicle listings
- View customer enquiries
- Manage test-drive bookings
- View dashboard statistics

## 💻 Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Website styling |
| JavaScript | Frontend functionality |
| Python | Backend programming |
| Flask | Web framework |
| SQLite | Database |
| Bootstrap | Responsive UI (optional) |

## 📂 Project Structure

```text
AUTOHUB/
│
├── app.py
├── requirements.txt
├── README.md
├── .env.example
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── cars.html
│   ├── car_details.html
│   ├── compare.html
│   ├── dashboard.html
│   └── contact.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
├── database/
│   └── autohub.db
│
└── README.md
```

*The structure is a suggested layout. Adjust it to match your actual project files.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd AUTOHUB
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

### 6. Open in Browser

```text
http://127.0.0.1:5000
```

## 🔐 Security

- Password hashing
- Input validation
- Secure session management
- Protected admin routes
- Environment variables for secret keys
- Database validation

## 🚀 Future Enhancements

- Online payment integration
- AI-based vehicle recommendations
- 360-degree car viewing
- Live chat with showroom agents
- Google Maps integration
- Real-time vehicle availability
- Mobile application
- Multi-language support

## 🎯 Project Objectives

1. Develop a user-friendly car marketplace.
2. Provide detailed
