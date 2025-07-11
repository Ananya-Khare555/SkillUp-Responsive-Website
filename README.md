# SkillUp-Responsive-Website

**SkillUp** is a responsive, user-friendly web application that enables users to register, log in, and access dynamic content across multiple pages such as Dashboard, Games, About, and Contact. It uses modern web technologies like Node.js, Express.js, MongoDB Atlas, EJS, and bcrypt for secure and seamless functionality.

---

## 🌟 Features

- 🔐 Secure User Registration & Login using **bcrypt** password hashing
- 📧 Login with either **username or email**
- 🌐 **MongoDB Atlas** for persistent cloud database storage
- 🎨 Responsive frontend using **EJS templating**
- 📁 Static files served cleanly from a `public/` folder
- ⚙️ Structured and modular **Express routing** for scalability

---

## 🧰 Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS (Embedded JavaScript Templates)
- **Database:** MongoDB Atlas
- **Security:** bcrypt (password hashing)
- **Config Management:** dotenv for environment variables

---

## 📂 Project Structure

SkillUp-Responsive-Website/
│
├── .env # Environment variables
├── public/ # Static assets (CSS, JS, images)
├── views/ # EJS templates
│ ├── homePage.ejs
│ ├── dashboard.ejs
│ ├── games.ejs
│ ├── about.ejs
│ ├── contact.ejs
│ ├── login.ejs
│ └── signup.ejs
├── app.js # Main application entry point
├── package.json # Node dependencies and metadata
└── README.md # Project documentation

---

## 🚀 Getting Started

### ✅ Prerequisites

- [Node.js](https://nodejs.org/) installed
- A [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account and URI

### 🔧 Setup Instructions

1. **Clone the repository**
2. **Install Dependencies**
3. **Configure environment variables**
4. **Start the server**

---

### 🔐 Security Highlights
- Passwords hashed using bcrypt before storing

- Email and username uniqueness enforced at DB level

- Error-handling for registration and login flows

- Environment variables protect sensitive config

### 👩‍💻 Author
Ananya Khare
🔗 GitHub: @Ananya-Khare555

### 📄 License
This project is open-source and available under the MIT License.

Website Link - https://skillup-m4sh.onrender.com/