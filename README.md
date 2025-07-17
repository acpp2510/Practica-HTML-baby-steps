# 🌐 BabyHTML5 – HTML5 Mini Project with Docker + NGINX

This project presents a simple biography of Tim Berners-Lee built using HTML5 and CSS. The content is served through an NGINX web server containerized with Docker.

---

## 📁 Repository

🔗 https://github.com/acpp2510/Practica-HTML-baby-steps.git

---

## 📦 Project Contents

- `index.html`: The main HTML page, structured with sections, lists, and basic formatting.
- `style.css`: Basic styles for customizing unordered list markers.
- `Dockerfile`: Configuration file for containerizing and serving the app using NGINX.

---

## ✅ Prerequisites

- [Docker](https://www.docker.com/get-started) must be installed and running on your machine.

---

## 🚀 How to Run the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/acpp2510/Practica-HTML-baby-steps.git
cd Practica-HTML-baby-steps
```

### 2. Build the Docker image
```bash
docker build -t baby-html .
```

### 3. Run the Docker container
```bash
docker run -d -p 80:80 baby-html
```

### 4. Open the application in your browser
Visit 👉 http://localhost

## 🛠 Technologies Used

- HTML5
- CSS
- Docker
- NGINX