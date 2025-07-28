# 🎧 Music Tracks Backend

This is the backend for the Music Tracks App, which provides a simple REST API to manage music tracks, genres, and tags.

> ⚠️ **Note:** This backend was not originally developed by me, but I have carefully explored and understood its structure, logic, and endpoints. It serves as a simple in-memory backend for this portfolio project.

## 🚀 Features

- REST API for tracks, genres, and tags
- Full CRUD functionality
- In-memory data storage (no external database)
- JSON-based request/response
- CORS support for frontend integration

## 🛠 Tech Stack

- Node.js
- Express.js
- `dotenv` (optional)
- JavaScript / TypeScript (depending on actual code)

## 📦 Install & Run

```bash
npm install
npm run dev

All data is stored in-memory and will reset on server restart.

Folder Structure

/data — Static data folder (genres, track uploads)

/src

__tests__ — Unit tests

config — App configuration (e.g., CORS, constants)

controllers — Request/response logic handlers

models — TypeScript models or entity definitions

services — Business logic and file operations

types — Shared TypeScript types

utils — Utility functions

index.ts — App entry point

routes.ts — API routes

seed.ts — Initial data import

🔗 Frontend

See the frontend repo: https://github.com/juliacodes2063/music-app-frontend

🖼 Demo

