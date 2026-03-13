# Stock Trading Web Application

A full-stack MERN (MongoDB, Express, React, Node.js) application for simulated stock trading. Users can register, login, view real-time stock data, and manage a virtual portfolio with a starting balance.

## 🚀 Features

- **User Authentication:** Secure registration and login using JWT and bcrypt.
- **Real-time Stock Data:** View a curated list of popular stocks with current prices.
- **Virtual Trading:** Buy and sell stocks using a virtual wallet balance ($10,000 starting).
- **Portfolio Management:** Track your holdings, total value, and profit/loss.
- **Responsive Design:** Modern UI built with React and custom CSS.
- **Express 5 Optimized:** Built with the latest Express 5 compatibility.

## 🛠️ Tech Stack

- **Frontend:** React, Vite, Axios, React Router.
- **Backend:** Node.js, Express 5, Mongoose.
- **Database:** MongoDB Atlas.
- **Authentication:** JWT (JSON Web Tokens).

## 💻 Local Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd stock-trading-app
   ```

2. **Install Dependencies:**
   Install root, backend, and frontend dependencies:
   ```bash
   npm install
   npm run build # This installs prefix dependencies and builds the frontend
   ```

3. **Environment Variables:**
   Create a `.env` file in the `backend/` directory:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_secret_key
   NODE_ENV=development
   ```

4. **Seed the Database:**
   Populate initial stock data:
   ```bash
   npm run seed
   ```

5. **Run the Application:**
   Start both backend and frontend in development mode:
   ```bash
   # From the root directory
   npm run server & npm run dev --prefix client
   ```
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:5000`

## 🌐 Deployment (Render)

1. **Environment Variables:**
   Set `NODE_ENV=production` and your `MONGO_URI` in the Render dashboard.
2. **Build Command:** `npm run build`
3. **Start Command:** `npm start`

## 📄 License
MIT
