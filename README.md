# 🛡️ Insurance Management System – Monik Group

A modern web-based insurance management platform built to manage customers, policies, and financial protection services efficiently.

---

## 🚀 Features

* 👨‍👩‍👧 Customer Management
* 📄 Policy & Insurance Tracking
* 💰 Financial Protection Services
* 🔐 Secure Authentication (Firebase)
* ☁️ Cloud Deployment (Firebase Hosting)
* 🤖 AI Integration (Gemini API – optional)

---

## 🏗️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript / Vite
* **Backend:** Firebase (Auth, Firestore, Hosting)
* **Deployment:** Firebase Hosting + GitHub Actions
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
insurance-management-monik-group/
│
├── public/                # Static files
├── src/                   # Main source code
├── .env.local             # Environment variables (not committed)
├── firebase.json          # Firebase configuration
├── package.json           # Project dependencies
└── README.md              # Project documentation
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/insurance-management-monik-group.git
cd insurance-management-monik-group
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Configure Environment Variables

Create a `.env.local` file and add:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_measurement_id
VITE_GEMINI_API_KEY=your_gemini_api_key
```

---

### 4️⃣ Run Locally

```bash
npm run dev
```

---

## 🚀 Deployment

### 🔹 Manual Deployment

```bash
npm run build
npm run deploy:all
```

---

### 🔹 Automatic Deployment (GitHub Actions)

Every push to `main` branch triggers deployment:

```bash
git add .
git commit -m "Deploy update"
git push origin main
```

---

## 🔐 GitHub Secrets Required

Add the following in:

**GitHub → Settings → Secrets and variables → Actions**

* FIREBASE_API_KEY
* FIREBASE_AUTH_DOMAIN
* FIREBASE_PROJECT_ID
* FIREBASE_STORAGE_BUCKET
* FIREBASE_MESSAGING_SENDER_ID
* FIREBASE_APP_ID
* FIREBASE_MEASUREMENT_ID
* GEMINI_API_KEY
* FIREBASE_SERVICE_ACCOUNT_JSON

---

## 🌐 Live Demo

```
https://your-project-id.web.app
```

---

## 📊 Firebase Console

* Hosting
* Firestore Database
* Authentication
* Analytics

---

## 🧪 Useful Commands

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run deploy:all   # Deploy full project
firebase status      # Check Firebase status
```

---

## ⚠️ Important Notes

* ❌ Do NOT commit `.env.local`
* ✅ Always use GitHub Secrets for sensitive data
* 🔐 Keep Firebase keys secure

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit pull requests.

---

## 📄 License

This project is licensed under the **MIT License**

---

## 👨‍💻 Developed By

**Monik Group**
Empowering lives with financial protection.

---

## 💬 Support

For support or queries, contact:
📧 [your-email@example.com](mailto:your-email@example.com)

---
