# 💰 Personal Finance Tracker

## 🧾 Introduction

The Personal Finance Tracker is a full-stack web application that helps users track their income and expenses, categorize them, and analyze their financial data through insightful charts and summaries. It empowers individuals to manage their money wisely, set budgeting goals, and stay in control of their financial health.

---

## 🛠 Project Type
**Fullstack** (Frontend + Backend + Database)

---

## 🚀 Deployed App

- **Frontend**: [https://your-frontend-url.com](https://finance-tracker-r31hdwepm-gadekar2003s-projects.vercel.app)
- **Backend**: [https://your-backend-url.com](https://finance-tracker-5mv4.onrender.com/)
- **Database**: MongoDB Atlas

---
## Screenshots:-
1)Dashboard 

<img width="1343" height="596" alt="image" src="https://github.com/user-attachments/assets/88d69efa-b5bd-4d1b-a8f5-6497f1c6ac98" /> </br>

2)Income Page

<img width="1349" height="590" alt="image" src="https://github.com/user-attachments/assets/063a0b20-7099-437c-97f9-9bcde7b3f1f9" /> </br>

3)Expense Page

<img width="1353" height="604" alt="image" src="https://github.com/user-attachments/assets/fc45896b-3e87-440b-9921-bdb4b600dd80" /> </br>

4)Budget Page

<img width="1340" height="596" alt="image" src="https://github.com/user-attachments/assets/5eb82bbb-95db-4e4a-8eaa-b12569221169" /> </br>

5)Saving Goals 

<img width="1338" height="598" alt="image" src="https://github.com/user-attachments/assets/36b32458-6d9b-4992-be14-8dcf8779f75f" />

## 📁 Directory Structure
```
my-finance-tracker/
├── backend/ # Node.js + Express API
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── index.js
│
├── frontend/ # Next.js + React UI
│ ├── components/
│ ├── pages/
│ ├── styles/
│ ├── utils/
│ ├── public/
│ ├── app/
```

---

## 🎥 Video Walkthrough

- **Features Demo (1-3 min)**: [Watch Video](https://www.youtube.com/watch?v=FngBe53_et8)
- **Codebase Overview (1-5 min)**: [Watch Video](https://www.youtube.com/watch?v=tFk5tIxglOg)

---

## 🌟 Features

- ✅ User authentication and authorization
- ✅ Add, edit, and delete income and expenses
- ✅ Category-wise breakdown of income/expenses
- ✅ Monthly summary chart (income vs expenses)
- ✅ Dashboard with visual insights
- ✅ Fully responsive design (Mobile + Desktop)
- ✅ JWT token-based secure APIs

---

## 🧠 Design Decisions & Assumptions

- Used **MongoDB** for flexible document-based data and easy aggregation
- Used **ShadCN + Tailwind CSS** for a consistent, accessible UI
- Used **Moment.js** for date formatting
- Backend API was kept RESTful for reusability and scalability
- Authentication is handled with token-based JWTs

---

## 🧪 Installation & Getting Started

### Backend

```bash
cd backend
npm install
npm start

### Frontend
cd frontend
npm install
npm run dev
🔐 Credentials (for demo)

Email: demo@example.com
Password: 123456

📡 API Endpoints
Base URL: /api

Authentication
METHOD	ENDPOINT	DESCRIPTION
POST	/auth/register	Register new user
POST	/auth/login	Login and get token

Income APIs
METHOD	ENDPOINT	DESCRIPTION
GET	/income	Get all incomes (user-based)
POST	/income	Add new income
DELETE	/income/:id	Delete income by ID

Expense APIs
METHOD	ENDPOINT	DESCRIPTION
GET	/expense	Get all expenses
POST	/expense	Add new expense
DELETE	/expense/:id	Delete expense by ID

Meta APIs
METHOD	ENDPOINT	DESCRIPTION
GET	/meta	Get monthly/category stats

🧰 Technology Stack
Frontend:
Next.js – React framework for SSR and routing

React – Component-based UI

Tailwind CSS – Utility-first styling

ShadCN – Accessible and styled UI components

Chart.js / Recharts – For data visualization

Lucide Icons – For modern icons

Backend:
Node.js – JavaScript runtime

Express.js – Lightweight web framework

MongoDB – NoSQL database

Mongoose – MongoDB ODM

Moment.js – Date manipulation

JWT – For secure authentication

