<div align="center">
  <br />
    <img src="assets/readme/hero.webp" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="Expo" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=F02E65" alt="Appwrite" />
  </div>

  <h3 align="center">Mobile Movie App — A Movie Finding App with Extensive Search</h3>

  <div align="center">
    Built by <a href="https://portfolio-kobamadev.vercel.app" target="_blank"><b>Mikael Kobama</b></a>, following the excellent step-by-step tutorial by <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a>.
  </div>
</div>

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🙌 [Credits](#credits)
6. 👤 [About Me](#about-me)

## <a name="introduction">🤖 Introduction</a>

This is a mobile movie discovery app built with Expo, TypeScript, and Tailwind CSS (via NativeWind), using Appwrite as the backend. The app fetches movie data and ranks titles by popularity based on real user search activity, offering a smooth, responsive browsing experience.

I built this project as part of my hands-on learning journey into React Native and mobile development, following the tutorial by **JavaScript Mastery** — full credit to them for the original project design and walkthrough. I adapted and rebuilt it to deepen my understanding of the stack and add it to my own portfolio.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Expo](https://expo.dev/)** — open-source platform for building universal native apps (Android, iOS, web) with JavaScript/TypeScript and React Native, featuring file-based routing, fast refresh, and native module support.
- **[React Native](https://reactnative.dev/)** — framework for building cross-platform mobile UIs with React's component-based, declarative model.
- **[Appwrite](https://appwrite.io/)** — open-source backend-as-a-service handling authentication, databases, file storage, and real-time messaging.
- **[TypeScript](https://www.typescriptlang.org/)** — statically-typed superset of JavaScript for safer, more maintainable code.
- **[Tailwind CSS](https://tailwindcss.com/) + [NativeWind](https://www.nativewind.dev/)** — utility-first styling brought to React Native for fast, consistent UI design.

## <a name="features">🔋 Features</a>

- 👉 **Real-time data** — fetches and displays live movie data
- 👉 **Home Page** — featured and trending movies
- 👉 **Search Page** — search for any movie
- 👉 **Popularity algorithm** — tracks user searches to surface the most popular titles

## <a name="quick-start">🤸 Quick Start</a>

**Prerequisites:** [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en), npm

```bash
git clone <your-repo-url>
cd mobile-movie-app
npm install
```

Create a `.env` file in the project root:

```env
EXPO_PUBLIC_MOVIE_API_KEY=
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=
```

Fill in your TMDB API key and Appwrite project credentials, then run:

```bash
npx expo start
```

Scan the QR code with the Expo Go app to view the project on your device.

## <a name="credits">🙌 Credits</a>

This project was built by following the tutorial from **[JavaScript Mastery](https://www.youtube.com/@javascriptmastery/videos)** — an incredible resource for learning modern web and mobile development. All original project concept, design direction, and teaching credit goes to their channel. If you're learning React Native or Expo, I highly recommend checking out their content.

## <a name="about-me">👤 About Me</a>

**Mikael Kobama** — Junior Full Stack Developer based in São Paulo, Brazil.

- 🔗 Portfolio: [portfolio-kobamadev.vercel.app](https://portfolio-kobamadev.vercel.app)
- 🔗 LinkedIn: _[add your link here]_
- 🔗 GitHub: _[add your link here]_

Open to opportunities, feedback, and connecting with other devs 🚀
