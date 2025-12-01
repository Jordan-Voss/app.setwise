# Setwise App

React Native / Expo mobile app for Setwise – a strength training companion.

## What it does (MVP)

- Fetches today's planned training day from the Setwise backend (`/api/today`).
- Shows block name, day name, and planned exercises.
- Future:
  - Log sets
  - Attach videos
  - Show history and stats

## Running locally

```bash
npm install
npx expo start
```
Make sure the backend is running on http://localhost:8080 (or update API_BASE_URL accordingly).