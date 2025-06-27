# 🌐 Fullstack PERN Auth App

This is a basic fullstack project I built to explore and gain hands-on experience with **PostgreSQL** and the **PERN stack** (PostgreSQL, Express.js, React, Node.js). It includes authentication, bot detection, rate limiting, and other essential real-world features.

The project helped me understand how to structure a fullstack application, manage both frontend and backend communication, and implement secure and user-friendly workflows.

---

## 🚀 Highlights

- 🌟 **Tech stack**: PERN (PostgreSQL, Express, React, Node.js) + TailwindCSS + DaisyUI  
- 🧠 **Global state management** with Zustand  
- 🐞 **Error handling** on both server and client sides  
- 🔒 **Rate limiting** & **bot detection** with Arcjet  
- 📦 **Modular structure** for scalability and clarity  
- ⚡ **Responsive UI** with Tailwind + DaisyUI  
- ⭐ **Free deployment** ready (e.g., on Render, Vercel, Railway)  
- ⏳ **.env-based config** for flexible environment management

---

## 🛠️ Tech Stack

**Frontend:**  
- React.js  
- Zustand  
- TailwindCSS  
- DaisyUI  

**Backend:**  
- Node.js  
- Express.js  
- PostgreSQL  
- Arcjet (for rate limiting & bot detection)  

---

## 📁 Setup Instructions

### 1. Clone the Repository

```bash
https://github.com/Shekhu04/PostgreStore.git
```

### 2. Configure Environment Variables

Create a .env file in the root folder and add the following:
```bash
PORT=3000

PGUSER=your_pg_user
PGPASSWORD=your_pg_password
PGHOST=your_pg_host
PGDATABASE=your_database_name

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

### 3. Install Backend Dependencies
```bash
npm install
npm run dev
```
Your backend server should start on http://localhost:3000.

### 4. Run the Frontend
```bash
cd frontend
npm install
npm run dev
```
Your frontend app will be live on http://localhost:5173 (or whatever port Vite chooses).
