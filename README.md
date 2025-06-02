**Description :**

# Nexily
Nexily is a modern, open-source matrimonial and social connection platform built with Bun.js, React, React Native, and Elysia.js. Designed for meaningful relationships, it features AI-powered matchmaking, real-time chat, verified profiles, and cross-platform accessibility all with a focus on culture.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 💞 Nexily

**Nexily** is a modern, open-source matrimonial and social connection platform built for **meaningful, culturally-aware matchmaking**. Designed for both individuals and communities, Nexily bridges technology with real-life relationship needs through **AI-powered matchmaking**, **real-time messaging**, and **secure social integrations** — all powered by **Bun.js**, **React**, **React Native**, and **Elysia.js**.

---

**📌 Project Purpose**

Nexily is more than just a dating app — it's a **people-first** initiative focused on:
- Helping individuals find long-term companionship or marriage
- Offering communities and governments a scalable, accessible matchmaking tool
- Promoting verified, culture-conscious relationships in a secure digital space

---

 **🧱 Tech Stack**

| Layer        | Tech Used                             |
|--------------|----------------------------------------|
| Frontend     | React (Web), TailwindCSS               |
| Mobile       | React Native (Expo), NativeWind        |
| Backend      | Bun.js + Elysia.js                     |
| Database     | SQLite (swappable with PostgreSQL)     |
| Real-time    | WebSockets (native in Bun)             |
| AI Features  | Onboarding assistant, preference scoring |
| Hosting      | Vercel (frontend), Railway/Render (API), Expo (mobile) |

---

 **🚀 Features :**

 **👤 Onboarding :**
- Human-like chatbot to collect bio-data
- Auto-capture profile photo + social links
- Preferences for marriage, dating, or friendship

 💞 Smart Matchmaking :
- Compatibility score based on interest, profession, culture, language
- Filter by religion, location, education, etc.
- Real-time match feed and suggestions

 **💬 Real-Time Messaging :**
- WebSocket chat with emojis, typing indicators, read receipts
- Match notifications and activity alerts
- Profile-based chat rooms

 **🌐 Social Media Linking :**
- Optional linking: Facebook, Instagram, LinkedIn, Twitter
- Enhances trust and improves match scoring
- Social icons displayed on user profiles (opt-in)

 **🧠 AI Onboarding Assistant :**
- Conversational onboarding to simplify registration
- Collects data and maps user preferences
- Stores responses securely in user profile table

 **🛂 Admin Dashboard :**
- Government and organization login for profile verification
- Inactivity monitoring, auto-deactivation
- Virtual meetup/event announcements


 **🗂️ Folder Structure :**

nexily/
├── backend/ # Bun.js + Elysia.js API and routes
├── frontend/ # React (Vite) + Tailwind web app
├── mobile/ # React Native (Expo) app
├── websocket/ # Real-time server logic
├── prisma/ # Database schema and client
├── public/ # Static assets
└── README.md
