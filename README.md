# 🎬 Netflix GPT

Netflix GPT is a full-stack AI-powered movie browsing app built with React, Firebase, and OpenAI. It delivers a Netflix-like experience with GPT-based smart search for movie recommendations and seamless TMDB integration.

---

## 🚀 Features

### 🔐 Authentication
- User Sign Up / Sign In with Firebase
- Form validation with `useRef`
- Profile updates (display name & avatar)
- Auth-protected routes with redirect logic
- Real-time auth state tracking
- Sign Out functionality

### 🎥 Movie Browsing
- Fetch movies from TMDB (Now Playing, Popular, etc.)
- Hero section with trailer autoplay & mute (YouTube embed)
- Responsive movie listings with Tailwind CSS
- Dynamic Movie Cards and Lists
- Custom Hooks: `useNowPlayingMovies`, `usePopularMovies`
- Redux store for user and movie state management

### 🧠 GPT Movie Search
- GPT-powered search bar using OpenAI API
- Generates movie suggestions based on user input
- Results enhanced with TMDB data
- Integrated with existing UI using reusable components
- GPT results managed via `gptSlice` in Redux

### 🌐 Bonus
- Multi-language support (i18n-ready)
- Memoization for performance boosts
- Responsive design for mobile/tablet/desktop

---

## 🧱 Tech Stack

- **Frontend**: React, TailwindCSS
- **State Management**: Redux Toolkit
- **Authentication**: Firebase Auth
- **APIs**:
  - TMDB API (for movie data)
  - OpenAI API (for GPT search)
- **Routing**: React Router
- **Video Embeds**: YouTube iFrame API

---

