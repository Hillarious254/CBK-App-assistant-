# CBK-App-assistant-
A React Native mobile app assistant for CBK to track investments, organize income, and provide financial insights.
# CBK Bond App — Assistant

A mobile-first React Native app that helps Kenyan retail investors discover upcoming Central Bank of Kenya (CBK) Treasury bills/bonds, run simple return calculators, log non-binding “intent to bid,” and track allocations, coupons, and maturities.

## ✨ Core Features (v1)
- Auction calendar with issue number, tenor, key dates
- Quick calculators (YTM, expected returns, laddering)
- Intent-to-bid flow (non-transactional)
- Notifications for auction results, settlement, coupon dates
- Micro-guides that explain bonds/bills in plain language
- Basic profile + KYC checklist status (read-only)

## 🧭 Product Goals
- **Clarity:** Reach the right auction page in ≤3 taps  
- **Education:** ≥50% of new users finish 1 micro-guide  
- **Conversion:** ≥25% of calculator users create an intent  
- **Retention:** ≥40% 30-day return rate for users with alerts

## 🏗️ Tech Stack
- **App:** React Native (Expo or bare RN)
- **State:** Redux Toolkit / Zustand (pick one)
- **Navigation:** React Navigation
- **API:** Node/Express (or Firebase) for auction data + notifications
- **Storage:** SecureStore/AsyncStorage; server DB (PostgreSQL)
- **Analytics/Crash:** Expo Analytics or Firebase + Sentry

## 📂 Project Structure (proposed)

## 🚀 Getting Started
1. **Clone**
   ```bash
   git clone https://github.com/<your-username>/CBK-App-assistant-.git
   cd CBK-App-assistant-

