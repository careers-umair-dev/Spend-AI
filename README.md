# SpendAI — AI-Powered Personal Finance Tracker

SpendAI is a full-stack personal finance management application that helps users track income and expenses, manage budgets, visualize financial activity, and receive AI-powered financial insights.

## 🚀 Features

* 🔐 User Registration & JWT Authentication
* 💰 Income & Expense Management
* 📊 Interactive Financial Dashboard
* 🎯 Budget Creation & Tracking
* 🏷️ Custom Expense Categories
* 📈 Financial Charts & Analytics
* 🤖 AI-Powered Financial Insights
* 💡 Personalized Saving Recommendations
* 📱 Responsive & Modern UI

## 🛠️ Tech Stack

**Frontend**

* React
* Vite
* Tailwind CSS
* React Router
* Axios
* Recharts

**Backend**

* Node.js
* Express.js
* PostgreSQL
* JWT
* bcrypt
* REST APIs

**AI**

* Google Gemini API

## 📁 Project Structure

```text
SpendAI/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── routes/
│   ├── scripts/
│   ├── sql/
│   ├── utils/
│   └── server.js
│
└── frontend/
    ├── public/
    └── src/
        ├── components/
        ├── context/
        ├── pages/
        ├── utils/
        ├── App.jsx
        └── index.css
```

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone <your-repository-url>
cd SpendAI
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=8000
DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
CLIENT_URL=http://localhost:5173
```

Run the backend:

```bash
npm run dev
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

Backend will run on:

```text
http://localhost:8000
```

## 🔑 Environment Variables

| Variable         | Description                    |
| ---------------- | ------------------------------ |
| `DATABASE_URL`   | PostgreSQL database connection |
| `JWT_SECRET`     | JWT authentication secret      |
| `GEMINI_API_KEY` | Google Gemini API key          |
| `CLIENT_URL`     | Frontend application URL       |
| `PORT`           | Backend server port            |

> Never commit your `.env` file or API keys to GitHub.

## 🤖 AI Integration

SpendAI uses Google Gemini to provide intelligent financial insights such as:

* Spending analysis
* Budget analysis
* Savings recommendations
* Monthly financial summaries
* Transaction analysis

## 🔒 Security

* JWT-based authentication
* Password hashing with bcrypt
* Protected API routes
* Environment-based secrets
* User-specific financial data

## 📄 License

This project is developed for educational, portfolio, and development purposes.

---

**SpendAI — Track. Analyze. Improve Your Finances.**
