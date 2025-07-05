# 💼 JobFlow

**JobFlow** is a full-stack job application tracker that helps users manage their job hunt with ease. Users can register, log in, and track job applications across different statuses like Applied, Interview, Offer, and Rejected — all in a clean and responsive UI.

---

## 🔗 Live Demo

👉 [Click here to view JobFlow](https://job-flow-wine.vercel.app/)

---

## 🚀 Features

### 🔐 Authentication
- User registration & secure login
- Protected dashboard using JWT
- Context-based auth management in frontend

### 📊 Dashboard
- View a list of job applications
- Add, update, delete applications
- Filter by application status
- Dynamic status count component
- Resume link & notes support

### 🧩 UI & UX Enhancements
- Responsive design for desktop & mobile
- Toast notifications for actions (login, add, delete, error, etc.)
- Blurred modal confirmation for deletions
- Clean layout and intuitive form handling

### 🧱 Reusable Components
- Application form with validation
- Status summary component
- Welcome message when not logged in

---

## 🛠️ Tech Stack

### Frontend
- React + Vite
- Tailwind CSS
- Axios
- React Router
- React Hot Toast

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT for Auth
- Bcrypt for hashing
- CORS + Dotenv

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Praneeth76/JobFlow.git
cd jobflow

```

### 2. Backend Setup (server/)
```bash
cd server
npm install
```

### Create .env inside server/:
```bash
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

### Run the backend
```bash
npm run dev
```

### 3. Frontend Setup (client/)
```bash
cd ../client
npm install
```

### Create .env inside client/:

```bash
VITE_API_URL=http://localhost:5000/api
```

### Run the frontend:
```bash
npm run dev
```

App will be available at http://localhost:5173

## 📄 License
- This project is licensed under the MIT License.
