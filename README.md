# 🐦 Twitter Clone

A full-stack Twitter-style social media app built with React, Vite, Tailwind, and Express — featuring authentication, posting, likes, comments, follow system, image uploads, and more.

![Alt text](public/readme-screenshot.png)

🌍 **Live Demo**  
👉 Check out the deployed app: [twitter-clone-gdgh.onrender.com](https://twitter-clone-gdgh.onrender.com/login)

---

## ⚙️ Tech Stack

- **Frontend:** React, Vite, TailwindCSS, DaisyUI, React Router, React Query
- **Backend:** Node.js, Express, MongoDB (with Mongoose)
- **Auth:** JSON Web Tokens (JWT), cookies
- **Image Uploads:** Base64 or Cloudinary (optional)
- **Deployment:** Render

---

Some Features:

-   ⚛️ Tech Stack: React.js, MongoDB, Node.js, Express, Tailwind
-   🔐 Authentication with JSONWEBTOKENS (JWT)
-   🔥 React Query for Data Fetching, Caching etc.
-   👥 Suggested Users to Follow
-   ✍️ Creating Posts
-   🗑️ Deleting Posts
-   💬 Commenting on Posts
-   ❤️ Liking Posts
-   🔒 Delete Posts (if you are the owner)
-   📝 Edit Profile Info
-   🖼️ Edit Cover Image and Profile Image
-   📷 Image Uploads using Cloudinary
-   🔔 Send Notifications
-   🌐 Deployment
-   ⏳ And much more!

---

## 🛠️ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/twitter-clone.git
   cd twitter-clone

---

- Install dependencies

- Backend:
  cd backend
  npm install

- Frontend:
  cd frontend
  npm install

---

# backend/.env.example
PORT=
MONGO_URI=
JWT_SECRET=
CLOUDINARY_API_KEY=

---

- Folder Structure:
  root/
├── backend/
│   └── server files (Express, DB models, routes)
├── frontend/
│   └── client-side app (React + Vite)
├── public/
│   └── static assets
