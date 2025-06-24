[![Build Status](https://img.shields.io/github/actions/workflow/status/shroomtop/2player-chatgpt/ci-html.yml?branch=main)](https://github.com/shroomtop/2player-chatgpt/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE.txt)
[![Release Version](https://img.shields.io/github/v/release/shroomtop/2player-chatgpt)](https://github.com/shroomtop/2player-chatgpt/releases)
[![GitHub Pages](https://img.shields.io/github/pages/status/shroomtop/2player-chatgpt/main)](https://shroomtop.github.io/2player-chatgpt)

# 2player-chatgpt

Two‑player real‑time ChatGPT web client with shared message sync. Built in plain HTML + JS for local peer‑to‑peer usage—no backend, no login, privacy‑first.

## 🚀 Features
- Two users interact with ChatGPT concurrently via shared local state.
- Real‑time sync over WebSocket/peer connection (client‑only demo).
- Ultra‑simple single‑HTML deployment—embed anywhere, PWA capable.
- Mobile‑first responsive UI using CSS Grid/Flexbox.

## 📦 Getting Started
```bash
git clone https://github.com/shroomtop/2player-chatgpt.git
cd 2player-chatgpt
```

Open `index.html` in any modern browser.

For local network sync, run a WebSocket relay:
```bash
npm install -g websocket-relay-cli
websocket-relay --port 8081 /ws
```
Then open two browser tabs at:
- `file:///.../index.html`
- `http://localhost:8081`

## 🧪 Usage
- Type prompts into either player input field.
- Both players see full chat history.
- No data sent to any server except optionally ChatGPT API.

## 🛠️ Development
```bash
# Validate HTML
npx html-validator-cli --file=index.html
```

## 🤝 Contributing
1. Fork the repo.
2. Create a feature branch.
3. Submit a pull request with clear description and any relevant examples.

## 📄 License
Licensed under [MIT](LICENSE.txt), © 2025 Baxter, Minnesota, USA.

## 🔖 Topics
chat • realtime • multiplayer • chatgpt • html • web‑app
