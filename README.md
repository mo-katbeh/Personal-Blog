# 📝 Django Blog Project

A fully functional blog web application built with Django. This project allows users to create accounts, log in/out, publish blog posts, update/delete their content, and reset their password via email. It also features a clean UI using Bootstrap and crispy-forms.

---

## 🚀 Features

- User authentication (register, login, logout)
- Password reset via Gmail
- Create, update, and delete posts
- View other users’ posts
- Responsive UI with Bootstrap
- Crispy forms integration

---

## 🛠️ Tech Stack

- **Backend**: Django
- **Frontend**: HTML, Bootstrap 4
- **Database**: SQLite (default)
- **Email Service**: Gmail SMTP (using environment variables)

---

## 🔒 Environment Variables Setup

Create a `.env` file in your root directory and add:

```env
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USE_TLS=True
EMAIL_USER=your-email@gmail.com
EMAIL_PASSWORD=your-app-password
```
## 📦 Installation

Clone the repo:

```
git clone https://github.com/yourusername/django-blog.git
cd django-blog
```

Create and activate a virtual environment:
```
python -m venv venv
venv\Scripts\activate  # For Windows
```
Install dependencies:
```
pip install -r requirements.txt
Set up .env as explained above.
```
Run migrations:
```
python manage.py migrate
```
Start the server:
```
python manage.py runserver
```
## 🧪 Usage

- Go to http://127.0.0.1:8000/ in your browser

- Register a new user

- Create and manage your blog posts


🙋‍♂️ Author
Mohammad Katbeh

For inquiries or collaborations, feel free to connect!
mohammadkatbeh9@gmail.com
