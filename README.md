# 🚀 WordPress Docker Setup

This project provides a simple Docker Compose setup to run WordPress with MySQL.

## 📦 Tech Stack

* Docker
* Docker Compose
* WordPress
* MySQL

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/suitecrmdevashu/wordpress.git
cd wordpress-docker-setup
```

### 2. Create `.env` file

```bash
cp .env.example .env
```

Update values as needed.

### 3. Start containers

```bash
docker-compose up -d
```

### 4. Access WordPress

Open:
http://localhost:8083

---

## 🛠 Services

* **WordPress** → Port 8080
* **MySQL** → Port 3306

---

## ⚠️ Notes

* Do not commit the `.env` file
* Run `docker-compose down -v` if facing DB issues

---

## 💡 Future Improvements

* Add phpMyAdmin
* Add Nginx reverse proxy
* Enable SSL (Let's Encrypt)

---

## 👨‍💻 Author

Ashu Sharma
