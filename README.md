# 🌐 Udyog Saarathi – Empowering Opportunities for Persons with Disabilities

**Live App**: [udyo_saarathi.com](#)  
**GitHub Repo**: [GitHub Link](#)

> Udyog Saarathi is a socially-driven platform built to support **Persons with Disabilities (PWDs)** by connecting them to job opportunities, skill-enhancement resources, and educational tools — all in one place.

---

## 📌 Project Overview

**Udyog Saarathi** is a web-based platform that bridges the gap between job seekers with disabilities and available opportunities in both the **public** and **private** sectors. It offers real-time **job notifications**, **mock tests**, and **course recommendations** to aid the career advancement and learning journey of users.

Whether the goal is to prepare for government exams, build new skills, or land a private job, Udyog Saarathi serves as a one-stop solution — designed with accessibility and empowerment in mind.

---

## 🧩 Key Features

- 🔔 **Job Notifications**
  - Real-time alerts for public and private sector openings
  - Tailored listings based on disability category and qualification

- 📚 **Courses (Free & Paid)**
  - Curated list of online courses
  - Categorized by skill domain (IT, soft skills, exam prep, etc.)

- 🧪 **Mock Tests (Free & Paid)**
  - Test-based learning modules
  - Designed for competitive exams and industry roles

- 👥 **User Authentication & Profiles**
  - Secure login using Firebase Authentication
  - Save user preferences, test history, and progress

- 📱 **Responsive Design**
  - Mobile-first layout using Bootstrap and CSS media queries
  - Optimized for screen readers and accessibility tools

---

## ⚙️ Technologies Used

| Category            | Tools / Libraries                             |
|---------------------|-----------------------------------------------|
| 🎨 Frontend          | React.js, Bootstrap, CSS Media Queries         |
| 🛠️ Backend           | Node.js, Express.js                            |
| 🧠 Database          | MongoDB (with Mongoose ODM)                   |
| 🔐 Authentication    | Firebase Authentication + Realtime DB         |
| 📈 UI Responsiveness | CSS Media Queries, Bootstrap Grid             |

---

## 📁 Folder Structure

```
udyog-saarathi/
│
├── client/             # React Frontend
│   └── public/
│   └── src/
│       └── components/
│       └── pages/
│       └── assets/
│
├── server/             # Node + Express Backend
│   └── models/
│   └── routes/
│   └── controllers/
│   └── config/
│
├── firebase/           # Firebase Auth & DB Setup
│
├── README.md
└── .env                # Environment Variables
```

---

## 🚀 Running the Application

### 1. Clone the Repository
```bash
git clone <repository-url>
cd udyog-saarathi
```

### 2. Set Up Environment Files

#### `/client/.env`
```env
REACT_APP_API_URL=Your_Server_Domain
REACT_APP_FIREBASE_API_KEY=Your_Firebase_API_Key
...
```

#### `/server/.env`
```env
MONGO_URL=Your_MongoDB_Connection_URI
```

### 3. Install Dependencies & Run

#### Start Backend (Server)
```bash
cd server
npm install
nodemon server.js
```

#### Start Frontend (Client)
```bash
cd client
npm install
npm start
```

---

## 🗓️ Project Timeline

- **Start Date**: June 2024  
- **End Date**: August 2024  
- **Status**: ✅ Deployed & Functional  
- **Purpose**: Academic + Social Innovation Project

---

## 💡 Future Enhancements

- 🧩 AI-based job matching using user profile and test scores  
- 📲 Progressive Web App (PWA) support  
- 🌍 Multilingual support for regional languages  
- 📊 Admin Dashboard for analytics and job post control  
- 👨‍⚕️ Assistive tech features for screen readers, voice inputs

---

## 🙌 Final Note

**Udyog Saarathi** is not just a platform — it's a mission to empower persons with disabilities by giving them access to equal opportunities. Built with accessibility and scalability in mind, this application aims to be a long-term digital companion for job seekers striving to succeed despite physical challenges.

> 🌱 *Empowering lives. One opportunity at a time.*

---

**🧑‍💻 Contributors**: [Your Name Here]  
**📍 Built In**: India  
**📚 License**: MIT (optional)
