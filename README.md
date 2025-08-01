# 🏠 Homexa – Smart PG Finder

**Smarter stays for students — powered by Homexa.**

Homexa is a full-stack web platform designed to help students and young professionals find verified and affordable PG accommodations. Built using Flask and SQLite, it offers clean UI, secure authentication, and easy PG search/filtering.

---

## Features

- 🔍 Filter PGs by budget, location, and amenities  
- ✅ Verified listings only (no brokers)  
- 🔐 JWT-based user authentication (Flask-JWT-Extended)  
- 🛏️ Book or schedule PG visits  
- 📱 Responsive and student-friendly UI  

---

## 🛠 Tech Stack

**Frontend:**  
- HTML, CSS, JavaScript

**Backend:**  
- Python (Flask)

**Database:**  
- SQLite (via SQLAlchemy ORM)

**Authentication:**  
- JWT (Flask-JWT-Extended)

**Hosting:**  
- Vercel (Frontend), Render/Railway (Flask backend)

---

## 📂 Project Structure

```
homexa/
├── client/                  # Frontend files
│   ├── index.html
│   ├── styles/
│   ├── scripts/
│   └── assets/
├── server/                  # Flask backend
│   ├── app.py
│   ├── models.py
│   ├── routes/
│   ├── auth/
│   ├── static/
│   ├── templates/
│   └── database.db          # SQLite file
├── docs/                    # Documentation and PRD
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
| 2    | Frontend layout, SQLite models, JWT auth  |
| 3    | Feature integration, filters, booking     |
| 4    | Testing, deployment, final presentation   |

> 🗓 Started on **July 25, 2025** – ongoing development

---

## 🧪 Run Locally

### Backend
```bash
cd server
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
```

### Frontend
Open `client/index.html` in your browser or use VS Code Live Server.

---

## 📄 License
This project is licensed under the MIT License.
