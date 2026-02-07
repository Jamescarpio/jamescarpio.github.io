# James Carpio — Portfolio (Vite + React)

A modern personal portfolio built with **React + Vite** and styled with **Tailwind CSS**.

## Tech Stack
- React + Vite
- Tailwind CSS
- AOS (Animate on Scroll)
- Framer Motion
- Lucide Icons

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages (recommended)
### 1) Create a GitHub repo
Create a repo like: `james-portfolio`.

### 2) Set Vite base path
Edit `vite.config.js` and set `base` to your repo name:
```js
export default defineConfig({
  base: '/james-portfolio/',
  plugins: [react()],
})
```

### 3) Deploy
Use GitHub Actions (best) or manual deploy:

**Option A — GitHub Actions**
- Build and deploy `dist/` to `gh-pages`.

**Option B — Manual**
```bash
npm run build
# upload dist/ to GitHub Pages, or push dist to gh-pages branch
```

## Customize your info
Search and replace placeholders:
- Name: **James Carpio**
- Location: **Philippines**
- Links: GitHub / LinkedIn / Email

Files to edit:
- `index.html`
- `src/Pages/Home.jsx`
- `src/Pages/About.jsx`
- `src/components/Navbar.jsx`
- `src/components/SocialLinks.jsx`
- `src/Pages/Contact.jsx`

> Note: This template uses FormSubmit for contact form delivery. Replace the email in `src/Pages/Contact.jsx`.
