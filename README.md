# Sandaru Amarasinghe – Portfolio

Next.js 14 (App Router) · Tailwind CSS · Three.js (react-three-fiber) · Framer Motion. Frontend only, all data hardcoded.

## Run

```bash
npm install
npm run dev     # http://localhost:3000
npm run build && npm start
```

## Edit your content

Everything lives in `lib/data.ts` (profile, skills, experience, projects, education).
Replace `public/Sandaru_Amarasinghe_CV.pdf` to update the CV download.

## Structure

- `app/` – layout, page, global styles (white / dark theme tokens)
- `components/Scene.tsx` – the 3D hero (Three.js)
- `components/*` – Navbar, Hero, About, Skills, Experience, Projects, Education, Contact
- Theme toggle (light / dark) is saved in localStorage, default is dark.

## Deploy

Push to GitHub and import into Vercel (zero config).
