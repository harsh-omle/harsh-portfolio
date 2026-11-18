# Harsh Omle — Professional Portfolio

A responsive single-page professional portfolio built with React, TypeScript, Vite and Motion. Designed for professional and academic audiences.

## Requirements

- Node.js 20.19+ or 22.12+ (compatible with Vite 6)
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal (usually http://localhost:5173).

## Build

```bash
npm run build
npm run preview
```

## Customize

- `src/App.tsx` — all content, links, projects, experience, sections, and interactions.
- `src/styles.css` — colors, typography, spacing, layout and responsive styles.
- `public/portrait.png` — extracted from the portrait embedded in the supplied CV. Replace with a high-resolution photograph if desired.
- `public/Harsh_Omle_CV.pdf` — supplied CV; replace when updated.

## Deploy

Push the project to GitHub and import the repository into Vercel. Framework preset: Vite; build command: `npm run build`; output directory: `dist`.

## Notes

- The portfolio includes public professional links and email but intentionally excludes date of birth and telephone number from the webpage.
- Project illustrations are CSS-generated abstract visuals, not screenshots of real projects.
- Tomato is labeled as an academic project without a published source link.
- No backend is needed; contact uses a mailto link.
