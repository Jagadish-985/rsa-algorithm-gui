# RSA Algorithm — Alice & Bob

An interactive RSA encryption/decryption demo built as a single HTML file.

## 🚀 Deploy to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
vercel
```
Follow the prompts. Your site will be live in ~30 seconds.

### Option 2 — Vercel Dashboard (no CLI)
1. Go to https://vercel.com/new
2. Click **"Browse"** and upload this entire folder (or drag the zip)
3. Click **Deploy** — done!

### Option 3 — GitHub → Vercel (recommended for updates)
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new → Import Git Repository
3. Select the repo → Deploy
4. Every `git push` auto-deploys

## 📁 Files
| File | Purpose |
|------|---------|
| `index.html` | The entire app — HTML, CSS, and JS in one file |
| `vercel.json` | Vercel routing config |
| `README.md` | This file |

## 🔑 How to use the app
1. Enter two prime numbers (e.g. `p = 61`, `q = 53`)
2. Click **Generate Keys** — see n, φ(n), e, d computed step by step
3. Type Alice's message and click **Encrypt**
4. Click **Decrypt** to recover the original message
5. Each step shows the full per-character math table

## ✅ Requirements
- No dependencies, no build step, no Node.js required
- Pure HTML/CSS/JS — works in any modern browser
- Zero backend — everything runs client-side
# rsa-algorithm-gui
