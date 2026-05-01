Pavan Dange — 3D Portfolio  

A clean, interactive developer portfolio highlighting my work, skills, and experience.

Highlights
- 3D hero section with smooth animations and lighting
- Projects showcase (E‑commerce Platform, Social Media REST API, Customizable AI Agent)


Tech Stack
- React 19, Vite 6
- Three.js, @react-three/fiber, @react-three/drei, @react-three/postprocessing
- GSAP (animations)
- Tailwind CSS (via @tailwindcss/vite)


Live Demo
- Portfolio: (add your deployed URL here)

Getting Started
1) Install dependencies: `npm install`
2) Run locally: `npm run dev`
3) Build production: `npm run build`
4) Preview production: `npm run preview`

Environment Variables
Create a `.env` in the project root (no fallbacks — required for the contact form):
```
VITE_APP_EMAILJS_SERVICE_ID=your_service_id
VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
```

Deployment (free hosting)
- Netlify: build command `npm run build`, publish directory `dist`
- Vercel: framework preset `Vite`, build `npm run build`, output `dist`
- Cloudflare Pages: build `npm run build`, output `dist` (SPA fallback via `public/_redirects`)

Project Structure (key parts)
```
src/
  components/
    models/            # 3D scenes & effects (hero, tech cards, contact)
  sections/            # Page sections (Hero, Projects, Experience, Skills, Contact)
  constants/           # Content data (experience, projects, socials)
```

Available Scripts
- `npm run dev` — start dev server
- `npm run build` — production build
- `npm run preview` — preview production build
- `npm run lint` — run ESLint



