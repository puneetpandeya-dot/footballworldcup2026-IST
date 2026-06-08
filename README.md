# ⚽ FIFA World Cup 2026 — IST Schedule App

A clean, fast, single-file web app showing all 104 FIFA World Cup 2026 matches in **India Standard Time (IST)**. No build step, no dependencies, no server required.

## Features

- All 104 matches from Group Stage through the Final
- Times auto-converted from ET to IST (UTC+5:30)
- Filter by stage: Group / R32 / R16 / QF / SF / Final
- Live search by team name, venue, or date
- Fully responsive — works great on mobile
- Dark theme, zero external dependencies (except Google Fonts)

---

## 🚀 Deploy in 5 minutes

### Step 1 — Push to GitHub

```bash
# Clone or create a new repo on github.com, then:
git init
git add .
git commit -m "FIFA WC 2026 IST Schedule"
git remote add origin https://github.com/YOUR_USERNAME/wc2026-ist.git
git push -u origin main
```

### Step 2 — Deploy on Render (free)

1. Go to **[render.com](https://render.com)** and sign in with GitHub
2. Click **New → Static Site**
3. Select your `wc2026-ist` repository
4. Configure:
   - **Name**: `wc2026-ist` (or anything you like)
   - **Branch**: `main`
   - **Root Directory**: *(leave blank)*
   - **Build Command**: *(leave blank — no build needed)*
   - **Publish Directory**: `.`
5. Click **Create Static Site**
6. Render gives you a live URL like `https://wc2026-ist.onrender.com` in ~30 seconds ✅

---

## 🗂 File Structure

```
/
└── index.html      ← The entire app (single file)
└── README.md       ← This file
```

Everything is in `index.html`. No npm, no build tools, no server config needed.

---

## 🕐 Time Conversion

All times are converted from **US Eastern Time (ET / UTC-4)** to **India Standard Time (IST / UTC+5:30)** by adding 9 hours and 30 minutes. Conversion happens in the browser via JavaScript.

---

## License

Free to use and modify.
