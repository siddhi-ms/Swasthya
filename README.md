# Swasthya — Local development

Two folders were added: `frontend` (Vite + React) and `backend` (Node + Express).

From project root open two terminals (cmd.exe on Windows):

Frontend terminal:
```cmd
cd /d "C:\Users\SIDDHI SUSHIR\OneDrive\Desktop\Projects\Swasthya\frontend"
npm install
npm run dev
```

Backend terminal:
```cmd
cd /d "C:\Users\SIDDHI SUSHIR\OneDrive\Desktop\Projects\Swasthya\backend"
npm install
npm run dev
```

Open http://localhost:5173 for the frontend. API calls to `/api` are proxied to the backend at http://localhost:4000 during development.
