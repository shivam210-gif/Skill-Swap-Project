# Skill Swap Platform

A full-stack skill exchange platform built with React + Vite frontend and Express.js backend as separate deployable units.

## Quick Start

### 1. Start the Backend

```bash
cd skill-swap-backend
npm install
npm run dev
```

Backend runs on http://localhost:5000

### 2. Start the Frontend

```bash
cd skill-swap-frontend
npm install
npm run dev
```

Frontend runs on http://localhost:5173

### 3. Login with Demo Account

- Email: `alex@demo.com`
- Password: `demo123`

## Project Structure

```
skill-swap/
├── skill-swap-frontend/     # React + Vite + TypeScript
└── skill-swap-backend/      # Express.js API
```

See individual folder READMEs for detailed documentation.

## Features

- User authentication (JWT)
- Skill profiles and matching
- Swap request system
- Real-time chat (polling)
- Notifications
- Responsive design

## License

MIT
