# Abhiram Kolipaka — Portfolio

A modern, light-themed personal portfolio for a Computer Science graduate specializing in Data Science and Machine Learning. Built with TanStack Start (React 19), Vite 7, Tailwind CSS v4 and shadcn/ui.

## Quick start

```bash
# with bun (recommended)
bun install
bun dev

# or with npm
npm install
npm run dev
```

Then open the URL shown in the terminal (typically http://localhost:8080).

## Production build

```bash
bun run build   # or: npm run build
```

## Project layout

- `src/routes/index.tsx` — the whole single-page portfolio (hero, about, education, experience, skills, projects, certifications, achievements, contact).
- `src/routes/__root.tsx` — root layout, fonts, metadata and the global `<Toaster />`.
- `src/styles.css` — Tailwind v4 theme tokens and the light-theme design system.
- `src/components/ui/` — shadcn/ui components.
- `src/assets/abhiram-profile.png` — profile photo.
- `public/Abhiram_Kolipaka_Resume.pdf` — the resume served by the Download Resume button.

## Notes

- No database or API keys are required — the site is fully static content.
- Edit `src/routes/index.tsx` to update projects, skills, experience, or contact details.
