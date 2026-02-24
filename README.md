# WalletVN — Deploy to Vercel / GitHub

## Option A: Deploy via Vercel (easiest — 3 minutes)

1. Go to https://vercel.com → Sign up free (use GitHub login)
2. Click **"Add New Project"**
3. Click **"Import from GitHub"** — or use **"Deploy from template"** below
4. Upload this folder OR drag the folder onto Vercel's dashboard
5. Click **Deploy** — done! You get a URL like `walletvn.vercel.app`

### Then add to your Android home screen:
1. Open Chrome on your phone
2. Go to your Vercel URL
3. Tap the **⋮ menu** → **"Add to Home screen"**
4. Tap **Add** → it installs like an app with your wallet icon!

---

## Option B: Deploy via GitHub Pages (also free)

1. Go to https://github.com → Create new repository named `walletvn`
2. Upload all files in this folder to the repo
3. Go to repo **Settings → Pages**
4. Source: **Deploy from branch** → `main` → `/ (root)`
5. Save → your app is live at `https://yourusername.github.io/walletvn`

---

## Files in this folder

| File | Purpose |
|------|---------|
| `index.html` | The full WalletVN app |
| `manifest.json` | Makes it installable as Android app |
| `sw.js` | Service worker — works offline |
| `icons/` | App icons (192px + 512px) |
| `vercel.json` | Vercel caching config |

## Features
- 📊 Dashboard with income/expense stats
- 💳 Transaction ledger with edit/delete
- 🎯 Budget tracking (editable)
- 📷 Bank screenshot OCR (ZaloPay, MBBank, etc.)
- 💬 Bank SMS parser
- 📤 Export to Excel
- 💾 Data saved locally in browser (localStorage)
- 📱 Works offline after first visit
