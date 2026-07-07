# 🌾 KrushiFriendly

> Empowering Farmers Through Smart Agriculture 🚜

KrushiFriendly is a web-based agricultural platform that enables farmers to **rent farming equipment**, **buy quality seeds**, and receive **AI-powered recommendations** based on crops and soil conditions.

Built with **Django REST Framework**, **MySQL**, and modern web technologies, the platform aims to reduce farming costs, improve accessibility to agricultural resources, and promote sustainable farming practices.

---

## 📌 Table of Contents

- About
- Features
- Tech Stack
- System Architecture
- Screenshots
- Installation
- Project Structure
- API Endpoints
- Future Enhancements
- Contributors
- License

---

# 🌟 Features

### 👨‍🌾 Farmer Authentication
- User Registration
- Secure Login
- JWT Authentication
- Profile Management

### 🚜 Equipment Rental
- List Agricultural Equipment
- Upload Equipment Images
- Search Equipment
- Equipment Details
- Rent Request System
- Equipment Availability

### 🌱 Seed Marketplace
- Browse Seeds
- Buy Seeds
- Seed Details
- Category Filtering

### 📍 Smart Location Matching
- GPS Based Matching
- Location Filtering
- Nearby Equipment Search

### 💳 Payment System
- Razorpay Integration
- PayPal Support
- Cash on Delivery

### 🤖 AI Features
- Crop Recommendation
- Equipment Recommendation
- Smart Agricultural Assistant (Chatbot)

### 📊 Dashboard
- Equipment Management
- Rental History
- Transaction Records
- Profile Settings

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Backend

- Django
- Django REST Framework

## Database

- MySQL

## Authentication

- JWT Authentication

## Payments

- Razorpay
- PayPal

## Other Libraries

- Pillow
- Geopy
- Django CORS Headers

---

# 🏗 System Architecture

```
                Farmer
                   │
                   ▼
        Frontend (HTML/CSS/JS)
                   │
                   ▼
        Django REST Framework
                   │
      ┌────────────┼────────────┐
      ▼            ▼            ▼
 Authentication  Equipment   Seed Module
      │            │            │
      └────────────┼────────────┘
                   ▼
                MySQL
```

---




# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yashbabhulkar1729-del/KrushiFriendly.git
```

---

## Move into project

```bash
cd KrushiFriendly
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Activate

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Configure Environment Variables

Create a `.env`

```env
SECRET_KEY=your_secret_key

DEBUG=True

DB_NAME=your_database

DB_USER=root

DB_PASSWORD=your_password

DB_HOST=localhost

DB_PORT=3306
```

---

## Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## Run Server

```bash
python manage.py runserver
```

---

# 📂 Project Structure

```
KrushiFriendly/

│
├── accounts/
├── equipment/
├── seeds/
├── rentals/
├── payments/
├── chatbot/
├── static/
├── templates/
├── media/
├── requirements.txt
├── manage.py
└── README.md
```

---

# 🔗 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/register | Register User |
| POST | /api/login | Login |
| GET | /api/equipment | Equipment List |
| POST | /api/equipment | Add Equipment |
| GET | /api/seeds | Seed List |
| POST | /api/rent | Rent Equipment |
| GET | /api/profile | User Profile |

---

# 🚀 Future Enhancements

- Mobile Application
- AI Disease Detection
- Weather Forecast Integration
- Voice Assistant (Marathi)
- Crop Price Prediction
- Government Scheme Recommendation
- Multilingual Support
- Real-Time Chat Between Farmers

---

# 🏆 Achievements

🥇 Winner of **Aavishkar 2025**

🏅 University Level Innovation Project

Focused on improving accessibility of agricultural resources for farmers.

---

# 👨‍💻 Author

**Yash Gajanan Babhulkar**

B.Tech Artificial Intelligence & Data Science

KKWIEER, Nashik

GitHub:
https://github.com/yashbabhulkar1729-del

LinkedIn:
(Add your LinkedIn URL)

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push your branch
5. Create a Pull Request

---

# ⭐ Support

If you like this project,

⭐ Star this repository.

---

# 📜 License

This project is licensed under the MIT License.
