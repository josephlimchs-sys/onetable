# One Table — a Singapore hawker showcase (mockup)

Single-page static site: `index.html` + `assets/` (three real dish photos). Click **Chinese / Malay / Indian** in the nav and the whole page morphs — background color, giant background word, dish photo, and floating ingredient icons all switch together, styled after a Fruity/soda-brand product-tab pattern. No build step, no framework — vanilla HTML/CSS/JS using the Web Animations API for the idle float and parallax.

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
