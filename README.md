# Fullstack CI Demo App

A typical frontend-backend demo project with GitHub Actions CI.

## Structure

- `frontend/`: React + Vite
- `backend/`: Express API + node:test
- `.github/workflows/ci.yml`: CI workflow

## Run locally

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
npm install
npm test
npm start
```

API health endpoint:

- `GET /api/health`
