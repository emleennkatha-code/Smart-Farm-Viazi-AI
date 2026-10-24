# Smart Farm - Viazi AI Module
Enterprise-grade AI system for potato disease detection & market intelligence for Meru County.

## Problem Statement
- Meru farmers lose 30% of potato yield to Late Blight & Bacterial Wilt (Meru is Top 3 producer in Kenya)
- Potato price rose 32% in 2026 to Ksh 118/kg, but farmers lack price info and get exploited
- No offline AI solution for low-end Tecno phones with poor network

## Solution
- Offline AI (TFLite 20MB) - detects disease in <3 sec, 94% accuracy
- Treatment in Swahili / Kimeru / English + Voice
- Live market prices: Meru Gakoromone, Nairobi, Mombasa, Nakuru
- Agronomist Dashboard - disease hotspot heatmap for Twiga Foods scale

## Tech Stack (Enterprise)
- Frontend: Flutter (Android 8+ compatible)
- AI Engine: TensorFlow CNN trained on PlantVillage Potato (2152 images)
- Backend: Firebase Auth (Phone OTP), Firestore, Cloud Functions, Storage
- SDLC: Agile Scrum + Iterative Prototyping

## System Architecture
Mobile App (Flutter + TFLite) -> Firebase Backend -> Market Price API -> Admin Dashboard (React)

## Roadmap
- Sprint 0: Requirements & Design (This Week)
- Sprint 1: AI Model Training
- Sprint 2: Mobile App + Backend
- Sprint 3: Field Testing in Gakoromone Market
- Sprint 4: Deployment & Hackathon Pitch

## Team
BIT 2.1 - Meru University of Science and Technology
Built for scale: 100k smallholder farmers

## Status
Sprint 0 - In Progress

