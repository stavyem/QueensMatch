# Queens Match - Mentorship Matching Platform

A full-stack web application designed for the QueenB community to connect mentors and mentees for 1-on-1 professional guidance sessions.

Built during the QueenB x AppsFlyer Bootcamp.

## 🚀 Features

- **Mentor & Mentee Flow:** Mentees can browse available mentorship fields and submit match requests; mentors can manage and accept incoming requests.
- **Email Notifications:** Integrated with **Nodemailer** and **SMTP** to deliver instant email updates on request statuses and session updates.
- **Automated Cron Jobs:** Background tasks scheduled via **node-cron** to send pre-meeting reminders and post-meeting feedback forms.
- **Admin Management:** Role-based permissions allowing admins to manage user credentials and oversee platform activities.
- **Responsive UI:** Clean, accessible interface built with React and Material UI.

## 🛠️ Tech Stack

### Backend
- **Node.js** & **Express.js**
- **PostgreSQL** (Database)
- **Nodemailer & SMTP** (Email notifications)
- **node-cron** (Scheduled background jobs)
- **bcrypt** (Authentication & password hashing)

### Frontend
- **React 18**
- **Material UI (MUI)**
- **Axios**

---

## 📦 Project Structure

```text
QueensMatch/
├── server/                 # Express backend & API
│   ├── routes/            # API endpoints & authentication
│   ├── services/          # Nodemailer & Cron job workers
│   ├── index.js           # Entry point
│   └── .env.example       # Environment setup template
├── client/                # React frontend
│   ├── src/               # UI components, pages, & context
│   └── package.json
└── README.md