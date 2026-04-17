# 🛒 Django Product App (Mini Marketplace)

A simple web application built with Python and Django.
It allows managing products via admin panel and displaying them on a web page.

---

## 🚀 Features

* ✅ Admin panel (add / edit products)
* ✅ Database integration (Product model)
* ✅ Product listing page
* ✅ Basic frontend (HTML + CSS)
* ✅ Clean project structure ready for scaling

---

## 🧱 Tech Stack

* Python 3
* Django 6
* HTML5
* CSS3

---

## 📂 Project Structure

```id="struct01"
moj_projekt/
│
├── produkty/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── produkty/
│   │       └── lista.html
│   └── static/
│       └── produkty/
│           └── style.css
│
├── moj_projekt/
│   ├── settings.py
│   ├── urls.py
│
├── manage.py
```

---

## ⚙️ Setup & Installation

### 1. Clone repository

```id="clone01"
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 2. Install dependencies

```id="install01"
pip install django
```

### 3. Run migrations

```id="migrate01"
python manage.py migrate
```

### 4. Create admin user

```id="admin01"
python manage.py createsuperuser
```

### 5. Start development server

```id="run01"
python manage.py runserver
```

---

## 🌐 Access

* Main page:
  http://127.0.0.1:8000/

* Admin panel:
  http://127.0.0.1:8000/admin/

---

## 📸 Functionality Overview

* Add products via admin panel
* Display product list on homepage
* Basic styling with CSS
* Backend + frontend integration

---

## 🔥 Future Improvements

* [ ] Add product form (without admin panel)
* [ ] User authentication system
* [ ] Image upload for products
* [ ] Auction system (like eBay / Allegro)
* [ ] REST API (Django REST Framework)
* [ ] AI-based product recommendations

---

## 👨‍💻 Author

This project was created as part of learning Django and building a developer portfolio.

---

## 📜 License

For educational purposes.
