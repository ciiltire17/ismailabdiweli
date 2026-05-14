# Ismail Abdiweli Ahmed Portfolio

Premium personal portfolio website for a full-stack developer, AI/NLP researcher, creative designer, youth leader, and international learner.

## Current Version

This workspace contains a self-contained React + Tailwind + Framer Motion page in `index.html`.

It runs directly in the browser because the current machine has Node.js available but no `npm`, `pnpm`, or `yarn` command on the shell path.

## Included Branding Assets

```txt
assets/images/ismail-profile-main.jpg
assets/images/ismail-profile-about.jpg
assets/images/ismail-profile-alt.jpg
```

The main portrait is used in the hero section. The wider portrait is used in the About section.

## Included Certificates

Certificate files are stored in:

```txt
assets/certificates/
```

The portfolio links to these files from the Certifications section.

## Run

Open `index.html` in a browser.

Or serve it locally:

```bash
python -m http.server 4173 --bind 127.0.0.1
```

Then open:

```txt
http://127.0.0.1:4173/index.html
```

## Deploy To Vercel

Recommended project name:

```txt
ismailabdiweli
```

This gives a clean Vercel URL if the name is available:

```txt
https://ismailabdiweli.vercel.app
```

The project is static and Vercel-ready through `vercel.json`.

## Future Vite Setup

When a package manager is available:

```bash
npm install
npm run dev
```

Then the portfolio can be split into the recommended React folder structure:

```txt
src/
  components/
  data/
  sections/
  App.jsx
  main.jsx
```
