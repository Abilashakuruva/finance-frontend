# Personal Finance Visualizer 💰

A simple web application to track personal finances — built using **Next.js, React, Node.js, Express, MongoDB, Shadcn/UI, Recharts**.

## ✨ Features

- Add/Edit/Delete Transactions (amount, date, description)
- Transaction List View
- Monthly Expenses Bar Chart
- Predefined Categories (Food, Travel, Entertainment, etc.)
- Category-wise Spending Pie Chart
- Dashboard Summary (Total Expenses, Recent Transactions)
- Set Monthly Budgets
- Budget vs Actual Spending Comparison
- Simple Spending Insights

## 🛠️ Tech Stack

- **Frontend**: Next.js, React.js, Shadcn/UI, Recharts
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Hosting**: Vercel (Frontend), Render (Backend)

## 📂 Project Structure

/backend └── server.js (Express server) /frontend └── charts/ └── components/


## 🚀 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Abilashakuruva/finance-frontend

 ###  Backend Setup
 Navigate to backend folder: cd finance-backend
Install dependencies: npm install
Create a .env file and add your MongoDB connection string:
start backend server npm run dev

###  Frontend Setup
 Navigate to frontend folder: cd finance-visualizer
Install dependencies: npm install
start frontend server npm run dev

📦 Live Demo
Frontend (Vercel): https://finance-frontend-olive.vercel.app
Backend (Render): https://finance-backend-box1.onrender.com
📸 Screenshots
image1: https://res.cloudinary.com/dzwzh1wki/image/upload/v1745850004/Screenshot_2025-04-28_194451_yxx8o4.png
image2: https://res.cloudinary.com/dzwzh1wki/image/upload/v1745850004/Screenshot_2025-04-28_194739_ms2xsb.png
image3: https://res.cloudinary.com/dzwzh1wki/image/upload/v1745850005/Screenshot_2025-04-28_194812_bdvllx.png
video:
https://www.youtube.com/@abhilashaabhi4290











# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
