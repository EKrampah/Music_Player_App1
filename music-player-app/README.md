

# 🎵 Music Player App

A responsive, theme-aware music player built with **React**, **Tailwind CSS**, and integrated with the **Deezer API**. This app allows users to search for music tracks, view details, and play preview clips directly in the browser.

## 🚀 Features

- 🔍 **Search Functionality** – Search for tracks, artists, or albums using the Deezer API.
- 🎧 **Music Preview Playback** – Stream 30-second audio previews from Deezer.
- 🧱 **Component-Based UI** – Modular React components: `SearchBar`, `TrackCard`, and `MusicPlayer`.
- 🌗 **Dark Mode Toggle** – User-controlled light/dark themes with localStorage persistence.
- ⚠️ **Error Handling** – Graceful feedback for API errors or empty results.

## 🛠️ Tech Stack

- **React** + **Vite** for app scaffolding and performance.
- **Tailwind CSS** for utility-first, responsive styling.
- **Deezer API** for fetching music data and previews.

## 📦 Installation

```bash
npm create vite@latest music-player-app --template react
cd music-player-app
npm install
```

Then, install and configure Tailwind CSS following the [official Vite guide](https://tailwindcss.com/docs/guides/vite).

## 🔌 Deezer API Usage

The app fetches data using the Deezer public API:


The returned tracks are rendered with title, artist, album cover, and preview playback controls.

## 📲 Deployment

This app can be easily deployed on:
- **Netlify** and the link is:https://app.netlify.com/sites/merry-piroshki-f038bf/deploys

This platforms support React projects out-of-the-box.

## 🎯 Optional Enhancements

- Added a dark and light theme, hover effects for enhanced user experience.






<!-- # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

Here’s a concise and informative `README.md` for your music player app, based strictly on the provided document:

--- -->