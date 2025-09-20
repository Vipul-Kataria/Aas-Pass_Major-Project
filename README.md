Aas-Pass | Find What’s Around You

We often miss out on what's happening near us — maybe a local fest, a college event, or even a weather alert. That’s where **AAS-PAS** comes in.

This is a simple, useful website that shows you what’s going on *around you* — from nearby events and announcements to live weather updates.  

---

## 🚀 Try the Live Website

👉 https://aas-pass-major-project.onrender.com/

---

## 💡 Why Built This

The idea came from a common frustration: events and updates were scattered across WhatsApp groups, notice boards, and random posters.  
So, we thought — why not make **one platform** where anyone can check everything happening near them, just by selecting a city?

That’s how the concept of Aas-Pass took shape.

---

## 🔧 Technologies & Tools

This project was built using the MERN stack and a few external APIs.

- **Frontend:** HTML, CSS
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Templating:** EJS  
- **Deployment:** Render  
- **APIs Used:**  
  - AccuWeather API (for weather updates)  
  - Newsorg.in API (to fetch local events)  

---

## 🔍 Main Features

- 🌇 City selection to personalize your feed  
- 📅 Events listing fetched live using APIs  
- 🌦️ Weather info for selected city  
- 📢 Announcement page powered by MongoDB  
- ⚡ Smooth UI and user experience  

---

📂 Simple File Structure
📦 aas-pass-major-project/
├── 📁 data/               # Contains JSON-formatted static data
├── 📁 models/             # Mongoose schemas for MongoDB
├── 📁 node_modules/       # Auto-generated npm packages
├── 📁 public/             # Static files like CSS and images
│   └── CSS                 # Main stylesheet
├── 📁 routes/             # All the Express route handlers
├── 📁 utils/              # Utility functions
│   ├── errorHandler.js    # Centralized error handler
│   └── wrapAsync.js       # Helper to catch async errors
├── 📁 views/              # EJS templates for UI rendering
│   ├── ejs templates for all pages
├── .env                   # Environment variables (API keys, DB URI, etc.)
├── .gitignore             # Files and folders to ignore in Git
├── app.js                 # Main Express app entry point (links all routes)
├── middleware.js          # Custom middleware functions
└── schema.js 

