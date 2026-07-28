# One Table — a Singapore hawker showcase (mockup)

Single-page static site: `index.html` + `assets/` (three real dish photos, transparent PNGs, plus a hawker-centre photo used as the home screen background with a dark scrim). Opens on a home screen — scroll down (or click a pill/tab) to enter Chinese, then Malay, then Indian. Scroll up to go back, all the way to home. The background stays a fixed dark color throughout; only the giant word and dish photo (which floats/drops in with a slight bounce) animate on switch. Extra motion layer: sliding tab indicator, cursor-tilt on the dish photo, magnetic/ripple CTA, staggered page-load entrance, float-in text on every switch. No build step, no framework — vanilla HTML/CSS/JS using the Web Animations API and requestAnimationFrame.

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
