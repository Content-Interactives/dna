# DNA

React + Vite + TypeScript app rendering a 3D DNA model with **@react-three/fiber** and **@react-three/drei** (Three.js). Pedagogical content: [Standards.md](Standards.md).

**Live:** https://content-interactives.github.io/dna

## Requirements

- Node.js 18+  
- npm

## Commands

| Command | Description |
|---------|-------------|
| `npm install` | Dependencies |
| `npm run dev` | Vite dev server |
| `npm run build` | Production `dist/` |
| `npm run preview` | Preview `dist/` |
| `npm run lint` | ESLint |

Add a `deploy` script (for example gh-pages) if you need automated publishing; it is not defined in `package.json` today.

## Vite

`vite.config.ts` sets `base: '/dna/'` for GitHub Pages.

## Layout

- `src/App.tsx` — main scene / UI  
- `src/main.tsx` — React bootstrap  
- `index.html` — Vite entry  
- `dist/` — build output

## Stack

React 19, TypeScript, Vite 5/6, Three.js, React Three Fiber, Drei.
