# Twixel - A Twitter-Like Platform

## 🚀 Overview

Twixel is a **Twitter-like web application** built using **Django** where users can **post tweets** (text and images), **interact with highlights**, and **explore trending content**. The project follows **Django's DRY principle**, ensuring modular and reusable templates.

## ✨ Features

- **User Authentication** (Register/Login/Logout)
- **Create, Edit & Delete Tweets**
- **Highlights Section** (Featured tweets on the right side)
- **Search Functionality** (Filter tweets by keyword)
- **Responsive UI with Bootstrap**
- **Profile Mini Section** (User details on the left sidebar)
- **Tweet Detail View** (Open tweets in a separate page)

## 🛠 Tech Stack

- **Backend:** Django, SQLite/PostgreSQL
- **Frontend:** Bootstrap, HTML, CSS
- **Authentication:** Django's built-in auth system
- **Deployment:** (To be added - AWS/Heroku/Render)

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Horizon-1803/Twixel.git
cd Twixel
```

### 2️⃣ Create a Virtual Environment & Install Dependencies

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3️⃣ Apply Migrations & Run Server

```bash
python manage.py migrate
python manage.py runserver
```

Now, open **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)** in your browser. 🚀

## 📌 Future Improvements

- ✅ **Like & Comment System**
- ✅ **Follow/Unfollow System**
- ✅ **Real-time Notifications (WebSockets)**
- ✅ **Mobile App (React Native/Flutter)**

## 👨‍💻 Contributing

Pull requests are welcome! Feel free to **fork** the repo and submit PRs. 🙌

## 📜 License

This project is **MIT Licensed**. Feel free to use and modify it!

---

💡 **Let's build the future of social media, one tweet at a time!** 🐦🚀

