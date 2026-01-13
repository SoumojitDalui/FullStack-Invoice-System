# 🧾 FullStack Invoice System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Django](https://img.shields.io/badge/django-4.x-green.svg)
![React](https://img.shields.io/badge/react-18.x-blue.svg)
![Bootstrap](https://img.shields.io/badge/bootstrap-5.x-purple.svg)

A robust and modern Full-Stack Invoice Management System designed to streamline or organize your invoicing process. Built with power and scalability in mind using Django REST Framework and React.

---

## 🚀 Features

- **User Authentication**: Secure Sign Up and Sign In functionality.
- **Dashboard**: Interactive and responsive dashboard.
- **Invoice Management**: Create, Read, and View detailed invoices.
- **Itemization**: Add multiple items to invoices with dynamic rate and quantity calculations.
- **REST API**: Fully documented API endpoints for easy integration.
- **Responsive Design**: Built with Bootstrap for mobile-friendly usage.

---

## 🛠️ Technology Stack

### Backend
- **Framework**: Django & Django REST Framework
- **Database**: SQLite (Default) / PostgreSQL (Compatible)
- **Authentication**: JWT / Session

### Frontend
- **Library**: React.js
- **Styling**: Bootstrap 5
- **Routing**: React Router DOM

---

## 📂 Project Structure

```text
FullStack-Invoice-System/
├── invoicingApp/      # Django Backend App
├── invoicingUI/       # React Frontend Application
├── invoiving/         # Django Project Configuration
├── manage.py          # Django Management Script
└── db.sqlite3         # Database
```

---

## 🏁 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
- Python 3.8+
- Node.js & npm

### 1️⃣ Backend Setup (Django)

1. **Clone the repository**
   ```bash
   git clone https://github.com/SoumojitDalui/FullStack-Invoice-System.git
   cd FullStack-Invoice-System
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install django djangorestframework django-cors-headers
   ```

4. **Run Migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the Server**
   ```bash
   python manage.py runserver
   ```
   The backend will be available at `http://127.0.0.1:8000/`.

### 2️⃣ Frontend Setup (React)

1. **Navigate to the frontend directory**
   ```bash
   cd invoicingUI
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start the Development Server**
   ```bash
   npm start
   ```
   The app will automatically open at `http://localhost:3000/`.

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/user/signup/` | Register a new user |
| `POST` | `/user/login/` | User login |
| `GET` | `/invoices/` | List all invoices |
| `POST` | `/invoices/new/` | Create a new invoice |
| `GET` | `/invoices/<id>/` | flexible invoice details |
| `POST` | `/invoices/<id>/items/` | Add items to an invoice |

---

## 📸 Screenshots

*(Add your screenshots here)*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
