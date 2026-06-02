# Nabeeha Navaal Ahmed — Portfolio Site

A single-page, dark-minimal personal site tailored toward the **Field Strategist** role at BlueDot.
Static HTML/CSS/JS — no build step, no dependencies. Deploys to Vercel in ~2 minutes.

## Files
- `index.html` — the whole site (styles + scripts are inline)
- `favicon.svg` — browser tab icon
- `Nabeeha-Navaal-Ahmed-Resume.pdf` — linked from the "Download résumé" buttons
- `nabeeha-portrait.jpg` — **add this yourself** (see below)

To preview locally, double-click `index.html`.

---

## ⭐ Add your photo (1 step)
The About section is wired to show your photo. Just **drop your portrait into this folder and
name it exactly `nabeeha-portrait.jpg`**. That's it — refresh the page and it appears.
(Until you add it, a clean "NN" monogram shows in its place, so the site never looks broken.)
A portrait-orientation image works best (roughly 2:3, like the one you shared).

---

## Deploy to Vercel — pick ONE method

### Method 1 — Drag & drop (easiest)
1. Go to https://vercel.com and sign in (free Hobby plan is fine).
2. **Add New… → Project**, then drag this whole folder onto the dashboard.
3. It's detected as a static site automatically. Click **Deploy** → you get a `nabeeha.vercel.app` URL.

> Drag the *folder* (not just `index.html`) so the résumé, favicon, and photo come along.

### Method 2 — Vercel CLI
```bash
npm i -g vercel
cd nabeeha-portfolio-final
vercel          # accept defaults
vercel --prod
```

### Method 3 — GitHub + Vercel (best if you'll keep editing)
1. Push these files to a new GitHub repo.
2. Vercel → **Add New… → Project → Import** the repo → framework preset **Other** → **Deploy**.
3. Every future `git push` redeploys automatically.

---

## Custom domain (optional)
Project → **Settings → Domains → Add**, then point your DNS as Vercel instructs.

## Easy edits
- **Text:** open `index.html` and edit directly — it's plain HTML.
- **Add LinkedIn:** in the Contact section, find `Add your LinkedIn`, set your URL, and remove the `<!-- -->`.
- **Accent color:** change `--accent` near the top of the `<style>` block.
- **Replace résumé:** keep the filename `Nabeeha-Navaal-Ahmed-Resume.pdf` (or update the two links to it).
