🌸 Aarambika

Supporting Women’s Health from first periods to freedom years

📖 Overview

Aarambika is a women’s health and wellness web application designed to guide women through every stage of life — from their first period to menopause.
It provides tracking tools, AI-powered assistance, traditional Indian diet suggestions, communities, and gamification (Virtual Tree Growth) to make the journey healthier, easier, and more engaging.

🚩 Problem Statement

Women face many challenges across different stages of life:

Lack of clear, trusted guidance during their first period

Confusing or unreliable information about fertility and pregnancy

Limited support during menopause

No single platform that combines tracking, advice, community, and motivation


Aarambika solves these challenges with modern tech + traditional wisdom.

🌟 Key Features

🩸 Health Tracking

Period & fertility tracker

Symptom checker with AI support

Medicine & reminder notifications


🤖 AI Companion

Built with Google Gemini 1.5 Flash

Answers FAQs in regional languages

Suggests diet, exercise, and lifestyle changes


🍲 Traditional Diet & Wellness

Indian post-pregnancy diets

Remedies for late/irregular periods

Menopause nutrition & herbal suggestions


🧘 Exercise & Relaxation

Yoga & meditation guides

Relaxation music player


👭 Community Spaces

Dedicated groups for first period, pre-pregnancy, pregnancy, and menopause

Safe and anonymous interaction

Peer-to-peer support


🌱 Virtual Tree Gamification

Every healthy action (water intake, diet log, exercise, community help) → grows your tree

Tree stages: Seed → Sprout → Plant → Big Tree with flowers/fruits

Monthly leaderboard: Top 7 users rewarded with a real tree planted in their name 🌍

🏗 Tech Stack

Frontend: Next.js, React, Tailwind CSS, Framer Motion

Backend: Firebase Authentication, Firestore, Storage, Cloud Functions

AI: Google Gemini 1.5 Flash (AI Companion, Q&A, FAQs)

Gamification: SVG/Canvas for tree animations + Firestore for point system

Hosting: Firebase Hosting


🚀 Installation & Setup

1. Clone the Repository



git clone https://github.com/yourusername/aarambika.git
cd aarambika

2. Install Dependencies



npm install

3. Setup Firebase



Create a Firebase project at Firebase Console

Enable Authentication, Firestore, and Storage

Copy your config into .env.local


NEXT_PUBLIC_FIREBASE_API_KEY=xxxx
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=xxxx
NEXT_PUBLIC_FIREBASE_PROJECT_ID=xxxx
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=xxxx
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=xxxx
NEXT_PUBLIC_FIREBASE_APP_ID=xxxx

4. Run Locally



npm run dev

🛡 Security & Privacy

Firebase Authentication for secure login

Firestore rules restrict user data access to their own account

Community posts are anonymous by default for privacy

🌍 Future Scope

Wearables integration (Fitbit, Apple Watch, Google Fit for step/water sync)

AR Tree Experience (view your tree in your room using AR)

Multi-language support (Hindi, Marathi, other regional languages)

Telemedicine expansion (verified doctors for consultation)

👩‍💻 Team

Sameer Sayyad (Project lead)

Sadiq gonarkar(Team leader)

Kashif patel(Backend)

Shivani Bomble(Project Representative)

Shivangi Kulkarni (ideas & Research)

🙌 Acknowledgements

Hackathon: Kurukshetra Hackfest 2025 @ MIT Alandi, Pune

Inspired by real challenges faced by women across different life stages

Special thanks to mentors and community for guidance

🔥 Aarambika — A tree that grows with every healthy habit, for women and for the planet. 🌱
