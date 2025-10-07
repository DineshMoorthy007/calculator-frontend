# Distributed RMI Calculator

This is a **Distributed Calculator** project built in Java using **RMI (Remote Method Invocation)** for backend calculation and a **frontend hosted on GitHub Pages**.

The backend is hosted on **Render**, and the frontend GUI is hosted on **GitHub Pages**, allowing anyone to access the calculator online without installing anything.

---

## 🛠 Features

- Addition, subtraction, multiplication, division  
- RMI-based backend for distributed computing  
- Web-based GUI frontend  
- Hosted on Render and GitHub Pages  

---

## 📁 Project Structure

calculator-backend/ → Java Spring Boot backend with RMI support
frontend/ → HTML, CSS, JS frontend for the calculator

---

## ⚙️ How to Use

### Frontend:
Visit : https://dineshmoorthy007.github.io/calculator-frontend/

### Backend API Endpoints:
GET /api/calculator/add?a=5&b=3
GET /api/calculator/subtract?a=5&b=3
GET /api/calculator/multiply?a=5&b=3
GET /api/calculator/divide?a=5&b=3

## 🚀 Deployment

### Backend:
1. Deploy backend to Render using Docker.  
2. Expose port `8080` and enable `/api/calculator` endpoints.

### Frontend:
1. Push the frontend folder to a GitHub repository.  
2. Enable GitHub Pages in repo settings.  
3. Point frontend JavaScript to the backend URL.

---

## 📌 Notes

- Ensure the backend URL is correctly set in `script.js`:
- javascript
`const backendUrl = "https://rmi-calculator-backend-latest.onrender.com";
CORS must be enabled on backend for GitHub Pages frontend to work.`

📚 Technologies Used:

Java (Spring Boot, RMI)

HTML, CSS, JavaScript

GitHub Pages

Render (Cloud Hosting)

✨ Author
Dinesh moorthy S R — Distributed Calculator Project

📄 License
This project is licensed under the MIT License.
