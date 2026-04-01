# Wasm Stockfish

**Play chess in the browser against Stockfish, compiled to WebAssembly.** No server-side engine—analysis and play run locally in your tab. Includes puzzles, difficulty options, and installable PWA support.

[![Live demo](https://img.shields.io/badge/demo-wasm--stockfish.vercel.app-000?style=for-the-badge&logo=vercel)](https://wasm-stockfish.vercel.app)

## Features

- **Engine play** — Face Stockfish with adjustable strength (“difficulty”) and side choice.
- **Puzzles** — Curated positions with interactive solving.
- **Evaluation & history** — Move list and engine-style feedback for study and review.
- **PWA** — Add to home screen / offline-friendly where supported.

## Tech stack

| Area | Choice |
|------|--------|
| UI | TypeScript, Vite |
| Chess engine | [Stockfish](https://stockfishchess.org/) via **WebAssembly** |
| Hosting | [Vercel](https://vercel.com/) (static + edge-friendly) |

## Screenshots

<p align="center">
  <img width="32%" alt="Main board and game options" src="https://github.com/user-attachments/assets/948d9217-dc85-4ebc-b80c-b1f55f52fe32" />
  <img width="32%" alt="Puzzles list" src="https://github.com/user-attachments/assets/e922a285-2bf0-4d47-8f85-06dd27ec7c52" />
  <img width="32%" alt="Gameplay with move history" src="https://github.com/user-attachments/assets/1004640d-4af5-4142-928d-98c52f7934cb" />
</p>

## Local development

```bash
git clone https://github.com/trevsm/wasm-stockfish.git
cd wasm-stockfish
npm install
npm run dev
