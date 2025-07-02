# 🚀 ONEHUB – Integrated Platform for Daily Essential Services

ONEHUB is a full-stack web application that provides a unified interface for booking and comparing multiple daily essential services like food delivery, cab booking, hotel reservations, fuel delivery, and train ticket booking. It brings all fragmented services under one intelligent and AI-powered platform.

---

## 🔥 Features

- 🌐 **Centralized Platform** – No need to switch between apps like Swiggy, Zomato, Uber, MakeMyTrip, etc.
- 🔍 **Gemini AI Search Integration** – Ask your needs naturally, e.g., *"I want to order biriyani, cheap and fast"* and get smart results.
- 🧠 **OpenAI-Powered Personalization** – Personalized suggestions based on user behavior and location.
- 📍 **Location-Aware Services** – Get food and cabs based on your current GPS location.
- 📊 **Service Comparison** – View real-time price, ETA, and offers across multiple providers.
- 💳 **Secure Google Authentication** – Easy login and protected user data using Supabase Auth.
- ⚙️ **Supabase Backend** – Real-time database, Edge Functions, and secure API storage.

---

## 🛠️ Tech Stack

### Frontend:
- React.js (with TypeScript)
- Tailwind CSS
- Framer Motion
- Shadcn/UI components

### Backend:
- Supabase (Auth, Database, Edge Functions)
- Google Gemini Pro API (AI Search)
- OpenAI API (Recommendations)
- Zomato, Swiggy, Uber APIs (via REST / mock)

---

## 📦 Project Structure

├── src/
│ ├── components/
│ │ ├── GeminiSearchBar.tsx
│ │ ├── ServiceCards/
│ │ └── ...
│ ├── pages/
│ │ ├── Dashboard.tsx
│ │ ├── Services/
│ │ └── About.tsx
│ └── App.tsx
├── supabase/
│ ├── edge-functions/
│ └── supabase.config.ts
├── public/
├── package.json
├── .env
└── README.md


