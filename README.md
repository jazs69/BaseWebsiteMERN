🚀 MERN Stack Base Website
A production-ready MERN stack template that includes user authentication, protected routes, waste verification, and a responsive frontend built with React + Tailwind CSS. Perfect for launching full-stack web apps with modern tools.

🌟 Features
✅ User Registration & Login
Secure authentication using JWT and bcrypt for password hashing.

✅ Protected Routes
Restrict access to authenticated users only (e.g., dashboard, verify page).

✅ Responsive Frontend
Built using React, Tailwind CSS, and Vite for a blazing-fast dev experience.

✅ API with Express.js
RESTful endpoints for managing users and waste data.

✅ MongoDB Integration
Mongoose models for User, Waste, and BlacklistedToken.

✅ JWT Blacklisting for Secure Logout
Blacklist tokens on logout to prevent reuse.

📁 Project Structure

seiso-mern-base/

├── client/           # React + Vite frontend

│   └── src/

│       ├── components/

│       ├── context/

│       ├── pages/

│       └── assets/

└── server/           # Express + MongoDB backend

    ├── config/

    ├── middleware/

    ├── models/

    ├── routes/

    └── utils/

⚙️ Getting Started
🔧 Prerequisites
Node.js (v18+ recommended)

MongoDB Atlas or local MongoDB

🛠️ 1. Clone the Repository

git clone https://github.com/yourusername/seiso-mern-base.git
cd seiso-mern-base

🧪 2. Setup Backend (Express)

cd server
npm install

Create a .env file in server/:

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FRONTEND_URL=http://localhost:5173

Start the server:

npm start

🖥️ 3. Setup Frontend (React + Vite)

cd ../client
npm install

cd ../client
npm install

Create a .env file in client/:

VITE_BACKEND_URL=http://localhost:3000

Run the app:

npm run dev

🔗 Usage
Visit http://localhost:5173

Register, login, and navigate to the protected dashboard

Submit and verify waste to simulate rewards and interaction

📜 Available Scripts

🚀 Server (Express)

npm start       # Run backend server

💻 Client (React)

npm run dev     # Start dev server
npm run build   # Create production build
npm run lint    # Lint the code

🧰 Built With
✨ Frontend
React.js ⚛️

Tailwind CSS 💨

Vite ⚡

Axios

Framer Motion 🎞️

Lucide React Icons

🔧 Backend
Node.js + Express 🛠️

MongoDB + Mongoose 🧬

JWT Authentication 🔐

bcryptjs

cors

cookie-parser

dotenv

👤 Author
Jayesh Yadav
GitHub | LinkedIn | Email

🪪 License
This project is licensed under the MIT License.