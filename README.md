🎌 Anime Soulmates

<p align="center">
  <img src="https://files.catbox.moe/8oracy.jpg" alt="Anime Soulmates Banner" width="100%" style="border-radius: 20px;">
</p>

<h1 align="center">
  🎌 Find Your Perfect Anime Soulmate ✨
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/MongoDB-Database-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/Socket.io-Realtime%20Chat-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge">
</p>

<p align="center">
  <b>Connect with fellow anime fans who share your taste! From Shonen to Slice of Life, find your perfect watch buddy.</b>
</p>

---

🎀 DEVELOPER

<p align="center">
  <b>✨ Your Name ✨</b><br>
  <a href="RentaroAijo.4x">Facebook</a> •
  <a href="Dbz-Mahin7x">GitHub</a> •
  <a href="Instagram.com/dbz_mahin">Instagram</a>
</p>

---

🎯 LIVE DEMO

<p align="center">
  <a href="https://anime-soulmate.vercel.app/">
    <img src="https://img.shields.io/badge/🚀_Try_It_Now-Click_Here-ff69b4?style=for-the-badge&logo=vercel">
  </a>
</p>

<p align="center">
  <a href="https://anime-soulmate.vercel.app/">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://anime-soulmate.vercel.app/" alt="QR Code">
  </a>
</p>

<p align="center">
  <b>👉 <a href="https://anime-soulmate.vercel.app/">https://anime-soulmate.vercel.app/</a></b>
</p>

---

✨ FEATURES

 Feature Description
🔐 User Authentication Sign up and login securely
🎯 Anime Preferences Set favorite anime, genres, and bio
🤝 Smart Matching Find users with similar anime taste
💬 Real-time Chat Message your matches instantly
📝 Profile Management Edit your profile anytime
🎨 Beautiful UI Anime-themed purple gradient design
📱 Mobile Responsive Works on phone, tablet, and desktop

---

🛠️ TECH STACK

<p align="center">
  <img src="https://img.icons8.com/color/48/000000/html-5.png" width="50" title="HTML5">
  <img src="https://img.icons8.com/color/48/000000/css3.png" width="50" title="CSS3">
  <img src="https://img.icons8.com/color/48/000000/javascript.png" width="50" title="JavaScript">
  <img src="https://img.icons8.com/color/48/000000/nodejs.png" width="50" title="Node.js">
  <img src="https://img.icons8.com/color/48/000000/mongodb.png" width="50" title="MongoDB">
  <img src="https://img.icons8.com/color/48/000000/vercel.png" width="50" title="Vercel">
</p>

Technology Purpose
HTML5, CSS3, JavaScript Frontend
Node.js + Express Backend
MongoDB Atlas Database
Socket.io Real-time chat
JWT Authentication
Vercel Hosting & Deployment

---

📁 PROJECT STRUCTURE

```
📦 anime-soulmates/
├── 📂 api/                    # Backend API
│   ├── 📄 auth.js            # Login/Signup
│   ├── 📄 users.js           # User management
│   ├── 📄 matches.js         # Matching logic
│   ├── 📄 chat.js            # Chat endpoints
│   └── 📄 server.js          # Main server
├── 📂 public/                 # Frontend
│   ├── 📂 css/
│   │   └── 📄 style.css      # All styles
│   ├── 📂 js/
│   │   ├── 📄 auth.js        # Auth functions
│   │   └── 📄 dashboard.js   # Dashboard
│   ├── 📄 index.html         # Landing page
│   ├── 📄 login.html         # Login page
│   ├── 📄 signup.html        # Signup with anime prefs
│   ├── 📄 dashboard.html     # Swipe/browse profiles
│   ├── 📄 profile.html       # Edit profile
│   ├── 📄 matches.html       # View your matches
│   └── 📄 chat.html          # Real-time chat
├── 📄 .env                    # Environment variables
├── 📄 package.json            # Dependencies
└── 📄 vercel.json             # Vercel config
```

---

🚀 HOW TO DEPLOY YOUR OWN

📋 Prerequisites

· Node.js (v14 or higher)
· MongoDB Atlas account (free)
· GitHub account
· Vercel account (free)

---

⚡ One-Click Deploy

<a href="https://vercel.com/new/clone?repository-url=https://github.com/yourusername/anime-soulmates">
  <img src="https://vercel.com/button" alt="Deploy with Vercel">
</a>

---

📝 Step-by-Step Deployment

Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/anime-soulmates.git
cd anime-soulmates
```

Step 2: Install Dependencies

```bash
npm install
```

Step 3: Set Up MongoDB Atlas

1. Go to MongoDB Atlas
2. Create a free cluster
3. Click "Connect" → "Connect your application"
4. Copy your connection string

Step 4: Create .env File

Create a .env file in the root folder:

```env
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/anime-soulmates
JWT_SECRET=your-super-secret-key-change-this-123
```

Step 5: Test Locally

```bash
npm run dev
```

Open http://localhost:3000 in your browser

Step 6: Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/anime-soulmates.git
git push -u origin main
```

Step 7: Deploy to Vercel

Option A: Deploy via Vercel Website (Easier)

1. Go to Vercel
2. Click "Add New" → "Project"
3. Import your GitHub repository
4. Add environment variables:
   · MONGODB_URI = your MongoDB connection string
   · JWT_SECRET = your secret key
5. Click "Deploy"

Option B: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Follow prompts and add environment variables
```

Step 8: Update MongoDB Network Access

1. Go to MongoDB Atlas → Network Access
2. Click "Add IP Address"
3. Select "Allow Access from Anywhere" (0.0.0.0/0)
4. Click "Confirm"

---

✅ vercel.json Configuration

```json
{
  "version": 2,
  "builds": [
    {
      "src": "api/**/*.js",
      "use": "@vercel/node"
    }
  ],
  "routes": [
    {
      "src": "/api/(.*)",
      "dest": "/api/$1"
    },
    {
      "src": "/(.*)",
      "dest": "/public/$1"
    }
  ]
}
```

---

🌐 ENVIRONMENT VARIABLES

Variable Description Example
MONGODB_URI MongoDB connection string mongodb+srv://user:pass@cluster.mongodb.net/db
JWT_SECRET Secret key for JWT tokens your-super-secret-key-here

---

📱 PAGES & ROUTES

Page URL Description
🏠 Home / Landing page with features
📝 Sign Up /signup.html Create new account with anime preferences
🔑 Login /login.html Login to existing account
📊 Dashboard /dashboard.html Browse potential matches
👤 Profile /profile.html Edit your profile
💕 Matches /matches.html View your matches
💬 Chat /chat.html?user=ID Chat with matches in real-time

---

🤝 HOW MATCHING WORKS

1. Sign up and add your favorite anime & genres
2. Browse profiles of other anime fans
3. Like someone you're interested in
4. If they like you back → ✨ It's a match! ✨
5. Chat in real-time with your matches

---

💬 REAL-TIME CHAT FEATURES

· ⚡ Instant messaging with Socket.io
· 💾 Message history persistence
· 🟢 Online status indicators
· 👁️ Read receipts
· 📱 Mobile-friendly chat interface

---

🐛 TROUBLESHOOTING

❌ Black screen / Nothing loads

```bash
# Check if server is running
npm run dev

# Verify files in public/ folder
ls public/

# Check browser console (F12) for errors
```

❌ MongoDB connection error

· Verify MongoDB URI in .env
· Add 0.0.0.0/0 to Network Access in MongoDB Atlas
· Check if password has special characters (URL encode them)

❌ Can't chat with matches

· Check browser console for Socket.io errors
· Verify both users are matches
· Check if WebSocket connection is established

❌ Deployment errors on Vercel

```bash
# View logs
vercel logs

# Check if all files are pushed to GitHub
git status
```

---

📝 API ENDPOINTS

Method Endpoint Description
POST /api/auth/signup Create new account
POST /api/auth/login Login to account
GET /api/users/profile Get user profile
PUT /api/users/profile Update profile
GET /api/users/discover Get potential matches
POST /api/matches/like/:userId Like a user
GET /api/matches Get all matches
GET /api/chat/history/:userId Get chat history

---

🎨 CUSTOMIZATION

Change Colors

Edit public/css/style.css:

```css
:root {
    --primary: #764ba2;    /* Main purple */
    --secondary: #667eea;   /* Secondary blue */
    --accent: #ffd700;      /* Gold accent */
}
```

Add New Features

· Backend: Add new routes in /api/
· Frontend: Add logic in /public/js/
· UI: Modify HTML files in /public/

---

📞 CONTACT & SUPPORT

<p align="center">
  <a href="#">
    <img src="https://img.icons8.com/color/48/000000/facebook.png" width="40">
  </a>
  <a href="#">
    <img src="https://img.icons8.com/color/48/000000/github.png" width="40">
  </a>
  <a href="#">
    <img src="https://img.icons8.com/color/48/000000/twitter.png" width="40">
  </a>
  <a href="#">
    <img src="https://img.icons8.com/color/48/000000/gmail.png" width="40">
  </a>
</p>

<p align="center">
  <b>Live Website:</b> <a href="https://anime-soulmate.vercel.app/">https://anime-soulmate.vercel.app/</a>
</p>

<p align="center">
  <b>GitHub Repository:</b> <a href="#">https://github.com/Dbz-Mahin7x/anime-soulmate</a>
</p>

---

🤝 CONTRIBUTING

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

📄 LICENSE

```
© 2026 Anime Soulmates
Developed with 💜 for anime lovers everywhere
All Rights Reserved
```

---

🙏 ACKNOWLEDGMENTS

· 🎌 All anime fans who inspired this project
· 💜 The amazing Node.js and MongoDB communities
· 🏢 Studio Ghibli, Crunchyroll, and MyAnimeList for inspiration
· 👥 Everyone who tests and supports this project

---

⭐ SHOW YOUR SUPPORT

<p align="center">
  <b>Give a ⭐️ on GitHub if this project helped you!</b>
</p>

<p align="center">
  <a href="https://github.com/yourusername/anime-soulmates/stargazers">
    <img src="https://img.shields.io/github/stars/yourusername/anime-soulmates?style=for-the-badge&color=purple">
  </a>
  <a href="https://github.com/yourusername/anime-soulmates/network/members">
    <img src="https://img.shields.io/github/forks/yourusername/anime-soulmates?style=for-the-badge&color=blue">
  </a>
</p>

---

<p align="center">
  <img src="https://files.catbox.moe/8oracy.jpg" alt="Anime Soulmates Footer" width="200" style="border-radius: 50%;">
</p>

<p align="center">
  <b>Made with ❤️ and 🎌 for anime lovers everywhere</b>
</p>

<p align="center">
  <b>🇧🇩 From Bangladesh with Love 🇧🇩</b>
</p>

<p align="center">
  <img src="https://profile-counter.glitch.me/anime-soulmates/count.svg">
</p>

---

🚀 QUICK COMMANDS SUMMARY

```bash
# Install dependencies
npm install

# Run locally
npm run dev

# Deploy to Vercel
vercel --prod

# View logs
vercel logs

# Push to GitHub
git add .
git commit -m "Update"
git push
```

---

<p align="center">
  <b>✨ Happy Soulmate Hunting! ✨</b>
</p>