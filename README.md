# OLX Marketplace Clone

A full-stack OLX-style marketplace built with Node.js, Express, MongoDB, and a React + Vite client.

## Project structure

- `client/` — React frontend (Vite)
- `routes/`, `models/`, `middleware/` — Express API and MongoDB models
- `public/` — static assets and admin interface
- `data/` — location data

## Setup

1. Install backend dependencies: `npm install`
2. Install frontend dependencies: `cd client && npm install`
3. Create a `.env` file with your MongoDB connection string and JWT secret (never commit this file).
4. Start the backend: `npm start`
5. In another terminal, start the frontend: `cd client && npm run dev`

See the source files for the available API routes and application features.
