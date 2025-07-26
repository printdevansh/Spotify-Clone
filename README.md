# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 🎵 Spotify Clone – MERN Stack Project

A full-featured **Spotify Clone** built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. This app allows users to stream music, manage playlists, search for tracks, and enjoy a clean, responsive UI inspired by the real Spotify experience.

---

## 🚀 Tech Stack

- **Frontend**: React.js, Tailwind CSS / CSS Modules
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **File Storage**: Cloudinary / Local
- **Media Streaming**: HTML5 Audio API

---

## 🧩 Features

✅ User Authentication (Sign up / Login)  
✅ Browse and Play Songs  
✅ Create & Manage Playlists  
✅ Search Functionality (Songs, Artists)  
✅ Mobile Responsive Design  
✅ Audio Player with Controls  
✅ Admin Panel (Optional – upload songs, manage DB)

---

## 📸 Screenshots

> *(Add screenshots or screen recording here)*

---

## 🛠️ Installation

### Prerequisites:
- Node.js
- MongoDB
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/spotify-clone-mern.git
cd spotify-clone-mern

**2. Install Frontend & Backend Dependencies**
cd client   # React frontend
npm install

cd ../server   # Node backend
npm install

**3. Setup Environment Variables**
Create a .env file in the /server directory with:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

**4. Run the App**
# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm start
