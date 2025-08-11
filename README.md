# FreeStudy+ (minimal demo)

This archive contains a minimal skeleton for FreeStudy+ — a learning materials sharing site.
Folders:
- frontend/: static frontend (index.html, style.css, script.js)
- backend/: Node.js + Express skeleton with JWT auth, document routes, and AI endpoint (OpenAI)

Quick start (backend):
1. Install Node.js (>=16) and MongoDB (or use Atlas)
2. cd backend && npm install
3. Copy .env.example to .env and fill values (MONGO_URI, JWT_SECRET, OPENAI_KEY if you want AI)
4. npm run dev  (or npm start)

Frontend served statically by backend on /. You can also open frontend/index.html directly (some features require backend).
