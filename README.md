# 💪 Zane Fit

**Zane Fit** is a full-stack fitness planner web application built with **React**, **Express**, and **Node.js**. It helps users generate personalized workout plans based on their fitness goals, preferences, and lifestyle.

---

## 🚀 Features

- 🔍 User inputs age, weight, height, goal, fitness level, equipment, and more
- 📅 Dynamically generates an 8-week workout schedule
- 🥗 Nutrition recommendations based on TDEE and fitness goals
- 💡 Intelligent insights like BMI classification and equipment suggestions
- 📬 Connects frontend and backend via RESTful API

---

## 🛠️ Tech Stack

| Frontend | Backend | Hosting |
|---------|--------|---------|
| React (Vite) | Express.js | Vercel (Frontend) |
| Tailwind CSS | Node.js | Railway (Backend) |
| Axios | JSON API | |

---


---

## 🔗 Live Demo

- 🌐 Frontend: [https://zane-fit.vercel.app](https://zane-fit.vercel.app)
- ⚙️ API: [https://zanefit-express-production.up.railway.app](https://zanefit-express-production.up.railway.app)

---

## 🧠 How It Works

1. User visits the workout form at `/workout-form`
2. Inputs are submitted to the backend via `POST /api/workout`
3. Backend calculates BMI, TDEE, and creates a custom workout + nutrition plan
4. Personalized data is displayed on the frontend

---

#local developement
---Frontend Setup

1.cd client
2.npm install
3.npm run dev

---backend setup

1.cd server
2.npm install
3.node server.js


This project is licensed under the MIT License. Feel free to use, modify, and share!

🙌 Acknowledgements

Thanks to:
OpenAI
Railway & Vercel
The amazing open-source community ❤️



