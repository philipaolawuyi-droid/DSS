# GradConnect frontend and backend

## Run the complete demo

```bash
cd backend
npm install
PORT=4000 npm start
```

Then open `http://localhost:4000`.

The backend serves the frontend from `../frontend` and stores demo data in `backend/data.json`.

The frontend is also usable by opening `frontend/index.html` directly, where it uses browser localStorage.

## GitHub upload

Upload the contents of this folder to a repository. Do not upload `node_modules`.

GitHub Pages can host the standalone frontend, but it cannot run the Node.js backend. Use Render, Railway, Fly.io, or another Node.js host for the backend.
