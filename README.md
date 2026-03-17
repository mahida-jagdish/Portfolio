# Portfolio
A modern portfolio website built with AngularJS, Tailwind CSS featuring a responsive UI and a contact form with email integration using Nodemailer.
# 🌐 Portfolio Website with Contact Form

A modern full-stack portfolio website to showcase skills, projects, and experience.  
Includes a fully functional contact form that sends emails using Node.js and Nodemailer.

---

## 🚀 Features

- 🎨 Responsive UI (Tailwind CSS)
- 🌙 Dark Mode Toggle
- ⚡ Smooth animations (AOS)
- 📂 Project showcase section
- 📬 Contact form with email functionality
- 🔗 Full-stack integration (Frontend + Backend)

---

## 🛠️ Tech Stack

### Frontend:
- HTML5
- CSS3 (Tailwind CSS)
- JavaScript
- AngularJS

### Backend:
- Node.js
- Express.js

### Tools:
- Nodemailer
- Gmail SMTP

---

## 📁 Project Structure

```
project-folder/
│
├── index.html        # Frontend (AngularJS + UI)
├── server.js         # Backend (Express + Email API)
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Run the server
```bash
node server.js
```

Server will run on:
```
http://localhost:3000
```

---

## 📬 Contact Form Working

1. User fills the form  
2. Data is sent to backend using POST request  
3. Server processes data  
4. Email is sent using Nodemailer  

---

## 🔐 Security Note

⚠️ Do NOT expose your email credentials in production.  
Use environment variables instead:

```
process.env.EMAIL_USER
process.env.EMAIL_PASS
```

---

## 🚀 Future Improvements

- Add database (MongoDB/MySQL)
- Use modern framework (React/Angular)
- Deploy online (Vercel/Netlify/AWS)
- Add authentication system

---

## 📌 Author

**Jagdish**  
Full-Stack Developer
