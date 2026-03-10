# 🔨 Anvil & Hammer

**When you are the anvil, bear — When you are the hammer, strike.**

A digital diary built around a simple idea: patience earns power. Write for 7 days. On the seventh, declare your intention.

🔗 **[Open Anvil & Hammer →](https://ziqiaoonline.github.io/anvil-hammer/)**

---

## How It Works

**Days 1–6 (Bear):** You're the anvil. Write daily reflections on what's shaping you. Endure. Prepare.

**Day 7 (Strike):** The hammer is yours. Write a bold intention — something you're forging into being. The Strike saves with a flash of fire.

The cycle resets and continues. Bear for seven, strike on the seventh.

## Why Not a Streak Counter?

Most journaling apps track streaks — a number that goes up, turns red when you break it, and motivates through fear of loss.

Anvil & Hammer uses a different model. You're not maintaining a number. You're forging something. Miss a day and the forge cools — but your past work stays. The metaphor is cyclical and resilient, not linear and fragile.

Read more: [When Algorithms Meet Anthropology](https://ziqiaoonline.github.io/article-anvil-hammer.html)

## Features

- **7-day anvil/hammer cycle** with visual streak tracker
- **CRUD** — create, read, edit, and delete entries
- **Google Sign-In** with Firebase sync across devices
- **Offline mode** with localStorage fallback
- **PWA** — installable on mobile, works offline
- **Local timezone** — dates and greetings match your time
- **Strike archive** with ⚡ badges

## Install as App

**iPhone:** Open in Safari → tap Share → "Add to Home Screen"

**Android:** Open in Chrome → tap menu → "Install app"

**Desktop:** Chrome address bar → install icon (⊕)

## Tech Stack

- Vanilla HTML/CSS/JS (single file, zero dependencies)
- Firebase Auth + Realtime Database
- Service Worker for offline caching
- PWA manifest for installability
- Playfair Display + Source Serif 4 typography

## Project Structure

```
anvil-hammer/
├── index.html      ← The entire app
├── manifest.json   ← PWA config (name, icons, theme)
├── sw.js           ← Service worker (offline cache)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Run Locally

Just open `index.html` in any browser. Google Sign-In requires HTTPS or localhost.

---

Inspired by Edwin Markham's *Preparedness*.
Built by [Qiao](https://ziqiaoonline.github.io) with the belief that technology should carry care.
