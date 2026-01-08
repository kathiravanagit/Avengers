# Vite Project — Run Instructions

Prerequisites
- Node.js 16+ (LTS recommended).
- npm (bundled with Node) or `pnpm` / `yarn` if you prefer.

Quick start (PowerShell)

```powershell
cd "C:\Users\kathi\OneDrive\Desktop\Codes\avengers\vite-project"
npm install
npm run dev
```

Open the dev URL shown in the terminal (usually http://localhost:5173).

Build for production

```powershell
npm run build
```

Preview the production build locally

```powershell
npm run preview
```

Lint the project

```powershell
npm run lint
```

Alternative package managers
- pnpm: `pnpm install` then `pnpm run dev`
- yarn: `yarn` then `yarn dev`

Passing a custom port

```powershell
npm run dev -- --port 5174
```

Troubleshooting
- If dependencies fail to install, ensure your Node version meets the prerequisite and try deleting `node_modules` then reinstalling.
- If the dev server port is in use, pick a different port with the flag shown above.

Files of interest
- `index.html` — app entry HTML
- `src/main.jsx` — React entry
- `package.json` — scripts: `dev`, `build`, `preview`, `lint`

If you want, I can start the dev server here now and share the URL.``
