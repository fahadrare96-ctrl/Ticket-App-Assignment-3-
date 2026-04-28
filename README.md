# 🎬 CineBook — Ticket Booking App

A ticket booking app for Movies, Events, and Travel built with **React** (web) and **React Native** (mobile) using Expo.

---

## 📋 Assignment

**Course:** Mobile Application Development (MAD)

**Task:** Create a home screen that fetches a list of movies or events from a local database.

---

## ✅ Features

- Home screen displaying movies with title, genre, poster, and release date
- Search bar to filter movies by name in real time
- Dynamic list powered by `useState` and `useEffect`
- Local database (JavaScript array) simulating a real data source

---

## 🛠️ Tech Stack

| App | Technology |
|-----|------------|
| Web | React + Vite |
| Mobile | React Native + Expo |

---

## 📁 Project Structure

```
my-ticket-app/          ← React Web App
├── src/
│   └── App.jsx         ← Main home screen with search

my-ticket-app-mobile/   ← React Native Mobile App
├── app/
│   └── (tabs)/
│       └── index.tsx   ← Main home screen with search
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) (LTS version)
- [VS Code](https://code.visualstudio.com)
- [Expo Go](https://expo.dev/client) app on your phone (for mobile)

---

### Run the Web App (React)

```bash
cd my-ticket-app
npm install
npm run dev
```

Open your browser at: `http://localhost:5173`

---

### Run the Mobile App (React Native)

```bash
cd my-ticket-app-mobile
npx expo start
```

- Scan the QR code with **Expo Go** on your phone
- Or press `w` to open in browser at `http://localhost:8081`

---

## 🧠 Concepts Used

| Concept | How it's used |
|---------|---------------|
| `useState` | Stores search query and filtered movie list |
| `useEffect` | Re-filters the list every time the search query changes |
| Local Database | JavaScript array of movie objects (title, genre, date, rating) |
| `.filter()` | Filters movies by matching search query to title |
| `FlatList` (RN) | Efficiently renders the list in React Native |

---

## 📱 Screenshots

> Add screenshots here after running the app

---

## 👨‍💻 Author

**Fahad hussain**  
Mobile Application Development — 2026
