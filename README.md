# Ephemeral Secret Vault — Frontend Prototype

A responsive React + TypeScript + Vite frontend with a polished secret-sharing interface and interactive browser-only demo behavior.

## Requirements
- Node.js 18+ (20+ recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Build
```bash
npm run build
npm run preview
```

## What works in this frontend
- Landing page and responsive navigation
- Create text secret or select a file
- Expiration and one-time access controls
- Optional password field in the creation form
- Generated demo share link with copy action
- Secret reveal screen, copy, and consume behavior
- Local recent-secrets list and theme toggle
- Toast feedback and form validation

## Important security limitation
This is intentionally a **frontend-only prototype**. Secret content is held in browser memory/local storage for demo interactions and is **not encrypted or protected by a server**. Links are not usable by other devices or users. Do not enter real confidential information or upload sensitive files. Real one-time access, server-side encryption, secure file storage, rate limits, account permissions, and atomic consumption require a backend.

## Deploy
Build with `npm run build` and deploy the `dist` directory to a static host (Render Static Site, Netlify, or Vercel). No backend environment variables are needed for this demo.
