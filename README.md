# 🔨 Anvil & Hammer

**When you are the anvil, bear — When you are the hammer, strike.**

A digital diary built for people who find journaling hard.

If you've tried journaling apps and bounced off — the blank page felt too open, the streak counter felt like punishment, or your brain just couldn't show up every day — this app was designed with you in mind.

🔗 **[Open Anvil & Hammer →](https://ziqiaoonline.github.io/anvil-hammer/)**

---

## Who This Is For

Journaling shouldn't require a stable routine, a quiet mind, or perfect consistency. But most apps are built as if it does.

Anvil & Hammer is for people who:

- **Have ADHD** and struggle with open-ended prompts — the anvil/hammer structure gives you a clear role each day (today you bear, or today you strike), reducing decision fatigue
- **Deal with depression or anxiety** where showing up at all is an act of will — missing a day cools the forge, it doesn't break a chain or punish you
- **Are navigating big life transitions** — immigration, grief, career change — and need a space that holds weight without rushing you
- **Have tried journaling before and quit** because the app made them feel like they failed when they missed a day
- **Just want something simpler** — no templates, no mood trackers, no analytics dashboards. One text box. Write what you carry. That's it.

The 7-day cycle gives structure without rigidity. The forge metaphor gives meaning without pressure. And when you've earned the hammer, the Strike isn't a badge — it's *your words*, declaring what you're forging into being.

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
