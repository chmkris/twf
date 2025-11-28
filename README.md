# The Word In Fresh (TWF) — Starter Website

## What this contains
- Static front-end (HTML/CSS) inside `public/`
- Express server (`server.js`)
- `Dockerfile` for containerizing the app
- Placeholder logo and gallery images in `public/`

## Run locally
1. Install Node (v18+)
2. `npm install`
3. `npm start`
4. Open http://localhost:3000

## Docker
Build:
```
docker build -t twf-website:latest .
```
Run:
```
docker run -d -p 3000:3000 --name twf-website twf-website:latest
```
