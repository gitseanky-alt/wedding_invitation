# Sean & Joanna — Wedding Website

A clean, minimal, Apple-inspired static wedding invitation website for **Sean Kelly Yutiampo & Joanna Lorraine Castano** — **July 11, 2026**, Cebu, Philippines.

---

## 📁 Folder Structure

```
/
├── index.html       ← Main page (single-page site)
├── style.css        ← All styles
├── script.js        ← Countdown, scroll reveal, FAQ, nav
├── assets/          ← Place any supplementary images here
└── README.md
```

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it anything, e.g. `sean-and-joanna` or `wedding-2026`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Push the Files

If you have Git installed locally:

```bash
git init
git add .
git commit -m "Initial wedding site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages**
2. Under **Source**, select `Deploy from a branch`
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**

Your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO/
```
(Usually live within 1–2 minutes)

---

## ✏️ Easy Customization

All wedding details are in `index.html`. Search for any of these to update:

| What to change | Search for |
|---|---|
| Couple names | `Sean Kelly Yutiampo` |
| Date | `July 11, 2026` |
| Church address | `Cabrera, Mandaue` |
| Reception venue | `Bayfront Hotel` |
| Schedule times | `8:00 AM` |
| Color palette | `#080838` |
| FAQ answers | `.faq-answer` |

---

## 🗺️ Updating Map Embeds

The two Google Maps iframes use embedded search queries. To get precise embeds:

1. Go to [maps.google.com](https://maps.google.com)
2. Search for the venue
3. Click **Share → Embed a map**
4. Copy the `src="..."` URL from the `<iframe>` code
5. Replace the existing `src` in `index.html`

---

## 🎨 Color Palette

| Swatch | Hex |
|---|---|
| Deepest Navy | `#080838` |
| Dark Navy | `#111154` |
| Midnight Blue | `#191970` |
| Mid Navy | `#292C7B` |
| Soft Navy | `#393F86` |

---

## 📱 Features

- ✅ Fully responsive (mobile-first)
- ✅ Live countdown timer to July 11, 2026
- ✅ Smooth scroll reveal animations
- ✅ FAQ accordion
- ✅ Mobile hamburger nav
- ✅ Color swatch palette display
- ✅ SVG attire illustrations (no external images needed)
- ✅ Google Maps embeds
- ✅ Zero dependencies — pure HTML, CSS, JS
- ✅ GitHub Pages compatible (relative paths only)
