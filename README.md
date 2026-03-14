# 🎬 StreamHub — webOS Streaming Launcher

A futuristic, single-file streaming content browser and launcher designed for **webOS TV**.

## ✨ Features

- **Multi-region support** — US, Israel (IL), UK with region-specific providers
- **Provider filtering** — Netflix, Prime, Disney+, Max, Hulu, Apple TV+, Paramount+, YouTube, YES, HOT, Cellcom TV, BBC iPlayer, ITVX, Sky Go
- **Content type filter** — All / Movies / TV Shows
- **Genre chips** — dynamically generated, single-select filter
- **Real-time search** — searches title, overview, and genres with 200ms debounce
- **Sort options** — by rating, year (newest/oldest), title A–Z
- **Grid & List view** toggle
- **Favorites system** — heart button on cards and modal, persisted to `localStorage`
- **Watchlist** — add/remove, sidebar watchlist panel, dedicated tab
- **Stats panel** — total, showing, favorites, watchlist live counts
- **Tabs** — All / Favorites / Watchlist with live count badges
- **Detail modal** — poster, rating, genres, overview, per-region availability
- **Watch button** — triggers toast simulating webOS app launch
- **Dark / Light theme toggle** with persistence
- **Toast notifications** — animated slide-in for all actions
- **Keyboard shortcuts** — `Esc` closes modal, `Esc` in search clears it
- **Fully responsive** — sidebar collapses on mobile

## 🎨 Design

- **Orbitron** display font for futuristic headers and labels
- Neon cyan/blue/purple/pink color palette with glow effects
- CRT scanlines overlay
- Glassmorphism panels (`backdrop-filter`)
- Animated card hover with neon box-shadow glow
- Gradient animated header accent line
- Smooth modal slide-up animation

## 🚀 Usage

Just open `index.html` in a browser — no build step, no dependencies (fonts loaded from Google Fonts).

```bash
open index.html
# or
npx serve .
```

## 📁 Structure

```
streamhub/
├── index.html   # Everything — HTML + CSS + JS in one file
└── README.md
```

## 🔧 Roadmap / Ideas

- [ ] Connect to TMDB API for real poster images and data
- [ ] webOS TV deep-link integration (`window.webOS.service.request`)
- [ ] PWA support (manifest + service worker)
- [ ] Keyboard/remote-friendly D-pad navigation for TV
- [ ] User rating & notes
- [ ] "Continue Watching" section
- [ ] Trailer preview on hover

---

> Built with ❤️ for webOS TV. Single HTML file, zero dependencies.
