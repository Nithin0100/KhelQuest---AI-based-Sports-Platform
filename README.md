# KhelQuest — AI-Based Sports Platform

KhelQuest is a responsive sports-talent discovery and training platform. Athletes can build profiles, explore sports opportunities, track progress, and analyse push-ups, squats, and high jumps using browser-based pose detection.

---

## 🚀 Live Demo
https://khelquest-frontend.vercel.app

---

## ✨ Features

- Athlete onboarding, sport selection, and profile creation  
- Live-camera and uploaded-video exercise analysis  
- MediaPipe pose tracking for push-ups, squats, and high jumps  
- Training plans, daily targets, weekly progress, and achievement badges  
- Athlete rankings and performance milestones  
- Achievement uploads and athlete feedback  
- Finder for athletes, coaches, and nearby sports venues  
- Local sports board and SAI-focused opportunity views  
- Responsive navigation and layouts for desktop and mobile  

---

## 🧠 Tech Stack

- Frontend: React 18, TypeScript, Vite  
- Styling: Tailwind CSS  
- Pose Analysis: MediaPipe Pose  
- Icons: Lucide React  
- Deployment: Vercel  

---

## 📁 Project Structure

KhelQuest/
└── khelquest-frontend/
├── src/
│ ├── components/
│ │ ├── counters/
│ │ └── utils/
│ ├── App.tsx
│ ├── index.css
│ └── main.tsx
├── package.json
├── tailwind.config.js
└── vite.config.ts

---


---

## ▶️ Run Locally

### Prerequisites
- Node.js 18+
- npm

### Setup

```bash
git clone https://github.com/Spandana2012/KhelQuest---AI-based-Sports-Platform.git
cd KhelQuest---AI-based-Sports-Platform/khelquest-frontend
npm install
npm run dev


Open Application

Open the local URL displayed by Vite.Camera-based analysis requires browser camera permission; uploaded-video analysis can be used without it.

### 📦 Available Scripts

Run these commands from `khelquest-frontend/`:

| Command         | Purpose                              |
|----------------|--------------------------------------|
| npm run dev    | Start the development server         |
| npm run build  | Create a production build            |
| npm run lint   | Run ESLint checks                   |
| npm run preview| Preview the production build locally |


### Current Project Status

KhelQuest is currently a frontend prototype. Authentication, athlete profiles, rankings, bookings, messages, and several dashboard values use mock or client-side data. A production release would require persistent backend services, secure authentication, storage, and server-side validation.



