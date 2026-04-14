

# 🧠 MedPredic AI

**AI-Powered Medical Prediction & Assistance System**

---

## 🚀 Overview

MedPredic AI is a full-stack AI-powered web application designed to assist users in predicting potential medical conditions based on symptoms. It leverages modern frontend technologies, backend APIs, and AI integration to provide intelligent, real-time insights.


This project demonstrates strong skills in:

* Full-stack development
* AI integration (Gemini API)
* Firebase backend services
* Scalable architecture design


* website : https://ai.studio/apps/f635bc0a-2d88-42de-94ec-5ea1ad040bd4
---

## ✨ Features

* 🔍 **Symptom-based disease prediction**
* 🤖 **AI-powered analysis using Gemini API**
* 🔐 **Secure backend with Firebase**
* ⚡ **Fast UI built with Vite + React + TypeScript**
* 📊 **Structured data handling and type safety**
* 🌐 **Real-time interaction and response system**

---

## 🏗️ Tech Stack

### Frontend

* React (with TypeScript)
* Vite
* CSS

### Backend

* Node.js (Express via `server.ts`)
* Firebase (Firestore + Rules)

### AI Integration

* Google Gemini API

### Other Tools

* Firebase Config & Rules
* Environment-based configuration

---

## 📁 Project Structure

```
medpredic-ai/
│
├── src/                  # Frontend source code
│   ├── components/       # UI components
│   ├── lib/              # Utility functions
│   ├── firebase.ts       # Firebase config
│   ├── App.tsx           # Main app logic
│   └── main.tsx          # Entry point
│
├── server.ts             # Backend server
├── firestore.rules       # Firebase security rules
├── .env.example          # Environment variables template
├── package.json          # Dependencies & scripts
├── vite.config.ts        # Vite configuration
└── README.md             # Documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/AshishSingh297/medpredic-ai.git
cd medpredic-ai
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Setup Environment Variables

Create a `.env.local` file:

```env
GEMINI_API_KEY=your_api_key_here
```

---

### 4. Run the Application

```bash
npm run dev
```

App will run on:

```
http://localhost:5173
```

---

## 🔥 Backend Setup (Firebase)

1. Create a Firebase project

2. Enable Firestore

3. Update:

   * `firebase.ts`
   * `firebase-applet-config.json`

4. Deploy rules:

```bash
firebase deploy --only firestore:rules
```

---

## 🧠 How It Works

1. User inputs symptoms
2. Frontend sends request to backend
3. Backend processes and calls Gemini API
4. AI returns prediction/analysis
5. Results displayed in UI

---

## 📌 Use Cases

* Preliminary health assessment
* Educational medical tools
* AI-based healthcare prototypes
* Interview/demo project

---

## ⚠️ Disclaimer

This project is **not a medical diagnostic tool**.
It is intended for educational and demonstration purposes only.

---

## 🚧 Future Improvements

* User authentication system
* Medical history tracking
* More accurate AI fine-tuning
* Multi-language support
* Doctor consultation integration

---

## 🤝 Contributing

Contributions are welcome.
Feel free to fork the repo and submit a PR.

---

## 📜 License

This project is licensed under the MIT License.

---

