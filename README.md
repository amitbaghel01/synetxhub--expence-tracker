# Ledger — Expense Tracker

A minimal, responsive React expense tracker built for an internship project.

## Features
- Income, expense, and balance summaries
- Create, edit, and delete transactions
- Search, type filter, and month filter
- JSON Server mock API
- React hooks: useState, useEffect, useRef, useMemo, useCallback
- Responsive layout

## Requirements
Node.js LTS and npm.

## Run locally
Open this folder in VS Code, then run:

```bash
npm install
```

Open terminal 1 and start the mock API:

```bash
npm run api
```

Open terminal 2 and start Vite:

```bash
npm run dev
```

Visit the local URL shown by Vite (usually http://localhost:5173).

## Notes
The API is expected at http://localhost:3001/transactions. Keep `npm run api` running while using the app. Data is stored in `db.json` by JSON Server.

## Build
```bash
npm run build
```

For deployment, replace the local API URL in `src/hooks/useTransactions.js` with a hosted JSON API endpoint. Vercel alone does not host JSON Server as a persistent backend.
