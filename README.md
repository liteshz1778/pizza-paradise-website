# 🍕 Pizza Paradise - Static Pizza Ordering Website

A modern, responsive static pizza ordering website built using **HTML5**, **CSS3**, **Bootstrap 5**, and **JavaScript**.

This project demonstrates a simple restaurant website with multiple pages including Home, Menu, Offers, Login, Signup, Contact, and Order pages. The website is designed for educational purposes and can be deployed easily using Docker with the official Apache HTTP Server (`httpd`) image.

---

# 🚀 Features

- Responsive Design
- Bootstrap 5 UI
- Modern Navigation Bar
- Hero Section
- Pizza Menu
- Pizza Categories
- Offers Page
- Contact Form
- Login Page
- Signup Page
- Order Form
- Mobile Friendly
- Docker Ready
- Apache HTTP Server Deployment

---

# 🛠 Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Docker
- Apache HTTP Server (httpd)

---

# 📁 Project Structure

```
pizza-ordering-system/
│
├── index.html
├── menu.html
├── offers.html
├── order.html
├── login.html
├── signup.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   ├── hero.jpg
│   ├── veggleiaradisepizza.jpg
│   ├── peppypaneerpizza.jpg
│   └── nonvegsupremepizza.jpg
│
├── Dockerfile
└── README.md
```

---

# ⚙ Prerequisites

Before running this project, install:

- Docker

Verify installation:

```bash
docker --version
```

---

# 🐳 Running with Docker

## Build the Image

```bash
docker build -t pizza-paradise .
```

---

## Run the Container

```bash
docker run -d -p 8080:80 --name pizza-paradise pizza-paradise
```

Open your browser:

```
http://localhost:8080
```


---

# 📱 Pages
```
| Page    | Description                   |
|---------|-------------------------------|
| Home    | Landing page with hero banner |
| Menu    | Pizza categories and pricing  |
| Offers  | Promotional offers            |
| Order   | Static order form             |
| Login   | User login page               |
| Signup  | User registration page        |
| Contact | Contact information and form  |
```
---

# 📖 Future Improvements

- Backend Integration
- User Authentication
- Online Payment Gateway
- Shopping Cart
- Database Integration
- Admin Dashboard
- Order Tracking
- Email Notifications

---

# 👨‍💻 Author

**Litesh Zadane**

Static Pizza Ordering Website developed using HTML, CSS, Bootstrap, JavaScript, Docker, and Apache HTTP Server.

---
