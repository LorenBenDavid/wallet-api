<img width="1290" height="2796" alt="IMG_9879" src="https://github.com/user-attachments/assets/f200d5f6-5a56-432d-b252-d6fe697385f1" /># React Native Wallet – Personal Finance Tracker

A full-stack personal finance application that helps you **track income and expenses**, visualize summaries, and stay in control of your budget.  
Built as a student side-project to manage my own finances and now open for everyone to use or extend.

---

## 🚀 Features
- **Income & Expense Tracking** – log transactions and view real-time balance  
- **Statistics & Summaries** – total balance, categorized incomes and expenses  
- **Secure Authentication** – sign up / sign in with modern authentication  
- **Cloud Database & API** – persistent and scalable backend  
- **Cross-Platform Mobile App** – single codebase for iOS and Android  
- **Open Source** – anyone with an Expo account can clone and run it

---

## 🏗️ Tech Stack

### Mobile (React Native / Expo)
- **React Native + Expo** – cross-platform mobile development in one JavaScript/TypeScript codebase
- **Clerk** – authentication & user management (sign in/up, sessions)
- **Upstash** – managed Redis/Kafka for fast cache and real-time notifications

### Backend (Node.js / Express)
- **Node.js + Express** – RESTful API for transactions and summaries
- **Neon.tech** – serverless PostgreSQL database
- **Render** – cloud deployment for backend services

---

<img width="1290" height="2796" alt="IMG_9881" src="https://github.com/user-attachments/assets/192a4ef1-bccf-417f-a92a-a6a8d98fff56" />


<img width="1290" height="2796" alt="IMG_9879" src="https://github.com/user-attachments/assets/eda3cf84-bb28-4af4-a2c6-3b354a0694be" />


<img width="1290" height="2796" alt="IMG_9880" src="https://github.com/user-attachments/assets/7d813138-084c-4e1a-8e7c-f43f2663f376" />


---

## 🔧 Installation & Local Development

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- Git
- PostgreSQL account at [Neon.tech](https://neon.tech)
- Clerk account for authentication
- (Optional) Upstash account for Redis/Kafka

### 1. Clone Repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd react-native-wallet


2. Environment Variables
Create .env files in each part of the project:
backend/.env

DATABASE_URL=your_neon_connection_string
CLERK_SECRET_KEY=your_clerk_secret
UPSTASH_REDIS_URL=your_upstash_redis_url
UPSTASH_REDIS_TOKEN=your_upstash_redis_token

mobile/.env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
API_URL=https://<your-backend-render-url>

3. Install Dependencies
cd backend
npm install
cd ../mobile
npm install


4. Run Locally
Backend (Node/Express):

cd backend
npm run dev


Mobile (Expo):
cd ../mobile
expo start

🌐 Deployment
Backend – Deploy easily to Render
Database – Hosted on Neon.tech
Redis / Realtime – Hosted on Upstash
Mobile App – Built and published via Expo



