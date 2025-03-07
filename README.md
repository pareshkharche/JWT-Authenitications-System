# 🚀 JWT Authentication System  

A Django-based JWT authentication system providing secure user authentication with token-based authorization.  

## 🛠 Features  
- User Registration & Login with JWT authentication  
- Token-based access control  
- Password Reset via Email  
- Secure API endpoints  

## 📂 Project Structure  
```
JWT-Authentication-System/ 
│── core/                 # Main Django application
│── templates/account/    # Email templates for password reset
│── .dockerignore         # Docker ignore file
│── .gitignore            # Git ignore file
│── manage.py             # Django project management script
│── requirements.txt      # Python dependencies
│── README.md             # Project documentation
```

## 🚀 Installation & Setup  
### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/pareshkharche/JWT-Authenitications-System.git
cd JWT-Authenitications-System
```

### 2️⃣ Create a Virtual Environment  
```sh
python -m venv venv  
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies  
```sh
pip install -r requirements.txt  
```

### 4️⃣ Run Migrations  
```sh
python manage.py migrate  
```

### 5️⃣ Create a Superuser  
```sh
python manage.py createsuperuser  
```

### 6️⃣ Run the Server  
```sh
python manage.py runserver  
```
Your project is now running at `http://127.0.0.1:8000/` 🎉  

## 🔑 API Endpoints  
| Endpoint               | Method | Description               |
|------------------------|--------|---------------------------|
| `/api/register/`       | POST   | Register a new user       |
| `/api/login/`          | POST   | Login & get JWT token     |
| `/api/logout/`         | POST   | Logout user               |
| `/api/token/refresh/`  | POST   | Refresh access token      |
| `/api/password-reset/` | POST   | Password reset via email  |

## 🛠 Built With  
- **Python** 🐍  
- **Django & Django REST Framework**  
- **JWT (JSON Web Token)** for authentication  
- **PostgreSQL** for database  
- **Swagger** for API documentation  

---

## 📜 License  
This project is open-source under the **MIT License**.  
