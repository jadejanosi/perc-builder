# PERC Product Builder — Deploy to Vercel

## What's in this folder
- `index.html` — the complete app (everything in one file)
- `vercel.json` — tells Vercel how to deploy it
- `README.md` — this file

---

## How to deploy (step by step, no coding needed)

### Step 1 — Create a free Vercel account
Go to https://vercel.com and sign up with your email or GitHub account.

### Step 2 — Install Vercel CLI (one time only)
Open Terminal (Mac) or Command Prompt (Windows) and run:
```
npm install -g vercel
```
If you don't have Node.js, download it first at https://nodejs.org (click the LTS version).

### Step 3 — Deploy
In Terminal, navigate to this folder and run:
```
vercel
```
Follow the prompts:
- Set up and deploy? → Y
- Which scope? → your account
- Link to existing project? → N
- Project name? → perc-builder (or whatever you want)
- Directory? → ./ (just press Enter)
- Override settings? → N

Vercel will give you a live URL like: https://perc-builder.vercel.app

### Step 4 — Connect your own domain (optional)
1. Go to your Vercel dashboard
2. Click your project → Settings → Domains
3. Add your domain (e.g. tools.digitaleaseflow.com)
4. Follow Vercel's instructions to update your DNS in Namecheap

---

## Updating the app
Make changes to index.html, then run `vercel --prod` to redeploy.

---

## Need help?
The Vercel docs are at https://vercel.com/docs and are beginner-friendly.
