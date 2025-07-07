# 🚀 Crack‑Campus

[![Live Site](https://img.shields.io/badge/live%E2%80%91site-online-brightgreen.svg)]
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)]

## 🌐 Project Overview

Crack‑Campus is a one‑stop platform designed for engineering and university students. It provides free resources for **RGPV placement guidance**, including previous year questions, study notes, resume tips, and much more. The platform empowers students to effectively prepare for exams and campus placements.

Live Demo: [https://crackcampus.com/](https://crackcampus.com/)

---

## 🌟 Core Features

- 📚 **Study Resources:** Access previous year questions, syllabus, and curated notes.
- 🤖 **Mock Tests:** Practice aptitude, technical, and placement tests with time limits.
- 💼 **Placement Hub:** Resume-building tips, interview guidance, and off-campus placement support.
- 🔔 **Webinars & Workshops:** Participate in live sessions to boost career prospects.

---

## 🔧 Tech Stack

- **Frontend:** React (React Router, Material UI/Tailwind CSS)
- **Backend:** Node.js with Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT-based authentication
- **Deployment:** Vercel (Frontend), Render/Heroku (Backend)

---

## ⚙️ Getting Started (Local Setup)

### Prerequisites

- Node.js >= 14.x
- MongoDB (local or Atlas cluster)

### Installation

```bash
# Clone the repo
git clone https://github.com/shivuu2005/Crack-Campus.git
cd Crack-Campus

# Install dependencies for backend
cd server
npm install

# Install dependencies for frontend
cd ../client
npm install
```

### Configuration

Create `.env` files:

**server/.env:**
```
PORT=5000
MONGO_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
```

**client/.env:**
```
REACT_APP_API_URL=http://localhost:5000/api
```

### Running the App

#### Without Docker
```bash
# Run backend
cd server && npm run dev

# Run frontend in a separate terminal
cd client && npm start
```

Visit: `http://localhost:3000`

---

## 📂 Project Structure

```
Crack-Campus/
├── server/           # Backend API (Node.js + Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── index.js
├── client/           # Frontend (React)
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── contexts/
│       └── App.js
└── README.md
```

---

## 🧰 Testing (Optional)

```bash
# Backend tests
cd server && npm test

# Frontend tests
cd client && npm test
```

---

## 🤝 Contribution Guidelines

Contributions are welcome! To contribute:

1. Fork the repo
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Make changes & commit
4. Push to your fork and submit a Pull Request

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Thanks to contributors and community for support.
- Inspired by RGPV student placement needs.
- Built with love using open-source technologies.

---

### 📢 Connect with Me

**Shivam Malviya**
- GitHub: [@shivuu2005](https://github.com/shivuu2005)

---

> "Empowering students to crack exams and land their dream jobs." 🎓
