# Student Tracking — Aesthetic iPhone Prototype (Expo + React Native Paper)

A polished look & feel out of the box. Works with your public FastAPI URL so it runs on any network.

## Install & Run
```bash
npm install
npx expo start
```
Open with **Expo Go** on your iPhone.

## Configure API
Edit `src/api.js`:
```js
export let BASE_URL = 'https://your-fastapi.onrender.com';
```

## Screens
- Login (gradient header, outlined inputs)
- Parent (zone card, alerts list)
- Staff (zone chips, student list)
- Settings (update base URL)

## UI Stack
- React Native Paper (MD3 theme)
- expo-linear-gradient
- React Navigation
