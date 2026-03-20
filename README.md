# NagarMitra MVP

This repo contains both the backend API and the React Native mobile app scaffolding for the NagarMitra MVP.

## Structure

- `nagarmitra-backend/` – Node.js (JavaScript) Express API, MongoDB Atlas
- `nagarmitra-app/` – React Native app (Expo, JavaScript) – to be created

## Prerequisites

- Node.js >= 18
- A MongoDB Atlas connection string

## Getting Started

### Backend

1. Open `nagarmitra-backend/`
2. Install deps: `npm install`
3. Copy env: `.env.example` → `.env`
4. Fill `MONGODB_URI`
5. Run dev: `npm run dev`

Health:
- GET `http://localhost:4000/`
- GET `http://localhost:4000/api/v1/health`

### Mobile App (Expo)

We will scaffold the app using `create-expo-app` and add required packages (navigation, maps, camera, location, notifications, react-query, zustand, axios).

Run commands provided in the chat to initialize the app.
# NagarMitra_APP
