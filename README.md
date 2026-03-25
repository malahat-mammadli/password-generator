# 🔑 KeyForge — Password Generator

A sleek, pro-grade password generator built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no tracking — just fast, secure passwords in your browser.

---

## ✨ Features

- **Cryptographically secure** — uses `crypto.getRandomValues()`
- **Guaranteed character coverage** — ensures at least one character from each selected type, shuffled with Fisher-Yates
- **Adjustable length** — slider from 4 to 128 characters
- **Bulk generation** — generate 1 to 10 passwords at once
- **Character type toggles** — Uppercase, Lowercase, Numbers, Symbols
- **Exclude ambiguous characters** — removes O, 0, l, 1, I for readability
- **Strength indicator** — 5-level meter: Weak → Fair → Good → Strong → Perfect
- **Entropy display** — shows exact bit entropy so you know exactly how strong your password is
- **Active charset preview** — see every character in the pool before generating
- **Password history** — keeps your last 10 generated passwords, each individually copyable
- **One-click copy** — copies to clipboard with animated feedback
- **Fully client-side** — nothing is sent to any server, ever

---

## 🚀 Getting Started

No install. No signup. Just click and use:

👉 **[https://malahat-mammadli.github.io/password-generator/](https://malahat-mammadli.github.io/password-generator/)**

Works in any modern browser — desktop or mobile.

---

## 📁 Project Structure

```
password-generator/
└── index.html    # Everything — HTML, CSS, and JS in one file
└── README.md
```

---

## 🛡️ Security Notes

| Method | Detail |
|---|---|
| Randomness | `crypto.getRandomValues()` — CSPRNG, not `Math.random()` |
| Shuffle | Fisher-Yates algorithm — unbiased, uniform distribution |
| Storage | No passwords are stored, logged, or transmitted |
| Dependencies | None — no third-party scripts loaded at runtime |

> Fonts are loaded from Google Fonts. If you need fully offline use, replace the `<link>` tag with locally hosted fonts.

---

## 🎨 Design

Built with a dark theme and pink accent palette. Typography uses [Syne](https://fonts.google.com/specimen/Syne) for headings and [Space Mono](https://fonts.google.com/specimen/Space+Mono) for code and labels.

---

## 🌐 Live Demo

👉 [https://malahat-mammadli.github.io/password-generator/](https://malahat-mammadli.github.io/password-generator/)

Open the link — that's it. No account, no install, works for everyone.

---

## 📄 License

MIT — free to use, modify, and distribute.
