# One Table — a Singapore hawker showcase (mockup)

Single-page static site: `index.html` + `assets/` (three real dish photos, transparent PNGs). Opens on a dark home screen (logo, tagline, and cuisine pills) — scroll down (or click a pill/tab) to enter Chinese, then Malay, then Indian. Scroll up to go back, all the way to home. The whole page morphs on every switch — background color (via a radial wipe transition), giant background word, and dish photo (which now floats/drops in with a slight bounce) — styled after a Fruity/soda-brand product-tab pattern. Extra motion layer: sliding tab indicator, cursor-tilt on the dish photo, magnetic/ripple CTA, staggered page-load entrance, float-in text on every switch. No build step, no framework — vanilla HTML/CSS/JS using the Web Animations API and requestAnimationFrame.

## Deploy to Vercel (pick one)

**A. Vercel CLI (fastest)**
```
npm i -g vercel
cd one-table
vercel
```

**B. Drag and drop**
Go to https://vercel.com/new, choose "Deploy without Git", and drag this folder in.

**C. GitHub**
Push this folder (including the `assets/` folder — don't skip it, the photos won't load without it) to a new GitHub repo, then import it at https://vercel.com/new.

No environment variables, no `package.json`, no build step required.
