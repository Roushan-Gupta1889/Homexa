# 🏠 Homexa – Smart PG Finder

**Smarter stays for students — powered by Homexa.**

Homexa is a full-stack web platform designed to help students and young professionals find verified and affordable PG (Paying Guest) accommodations without the hassle of brokers. Built with modern technologies, Homexa simplifies the PG hunting process through location-based filtering, secure login, and clean UI.

---

## 🚀 Features

- 🔍 Filter PGs by budget, location, food availability, and more  
- ✅ Verified listings only (no fake entries)  
- 🔐 JWT-based user authentication and protected routes  
- 🛏️ Book or schedule PG visits easily  
- 📱 Responsive and mobile-friendly UI  

---

## 🛠 Tech Stack

**Frontend:**  
- HTML, CSS, JavaScript  

**Backend:**  
- Node.js + Express.js  

**Database:**  
- MongoDB (with Mongoose)  

**Authentication:**  
- JWT (JSON Web Token)  

**Hosting:**  
- Vercel (Frontend), Render/Railway (Backend)  

**Extras:**  
- Google Maps API (for PG location mapping)  

---

## 📂 Project Structure



```
├── client/                     # Frontend (HTML, CSS, JS)
│   ├── index.html
│   ├── styles/
│   │   └── style.css
│   ├── scripts/
│   │   └── main.js
│   └── assets/
│       ├── images/
│       └── icons/

├── server/                     # Backend (Express + MongoDB)
│   ├── app.js
│   ├── .env
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   └── pgController.js
│   ├── models/
│   │   ├── User.js
│   │   └── PG.js
│   ├── routes/
│   │   ├── auth.js
│   │   └── pg.js
│   └── middleware/
│       └── authMiddleware.js

├── docs/
│   └── README.md

├── .gitignore
└── README.md
```

---

## 👥 Team Members

| Name          | Role                          |
|---------------|-------------------------------|
| Mohit         | Project Manager & Backend Dev |
| Arpit Mehla   | Frontend Developer            |
| Roushan       | Backend Developer             |
| Amit Dole     | Testing & Deployment          |

---

## 📅 Timeline

| Week | Focus                                     |
|------|-------------------------------------------|
| 1    | Planning, PRD, wireframes, repo setup     |
| 2    | Frontend layout, backend models, JWT auth |
| 3    | Feature integration, filters, booking     |
| 4    | Testing, deployment, final presentation   |

> 🗓 Started on **July 25, 2025** – ongoing development

---

## 🧪 Run Locally

### Backend
```bash
cd server
npm install
npm run dev

