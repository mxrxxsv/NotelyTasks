# NotelyTasks

## Quick Start
1) Install dependencies
```sh
npm install
```
2) Start the dev server (HMR on by default)
```sh
npm run dev
```
   The console prints a local URL (usually http://localhost:5173). Open it in your browser.

## Common Tasks
- Lint the code
```sh
npm run lint
```
- Type-check + production build
```sh
npm run build
```
- Preview the production build locally
```sh
npm run preview
```

## Project Structure
- src/ – React components, styles, and entry points
- public/ – Static assets served as-is
- vite.config.ts – Vite configuration
- tsconfig*.json – TypeScript configs for app and tooling
- eslint.config.js – ESLint config
