# Sittas 2.2 — Meal Planner PWA

Personal meal planning app for the Sittas 2.2 diet plan.  
Schedule · Groceries · Checklist with prep reminders.

---

## Deploy to GitHub Pages (step by step)

### 1. Create a GitHub account (skip if you have one)
- Go to **github.com** and sign up — it's free.

### 2. Create a new repository
- Go to **github.com/new**
- Repository name: `sittas` (or whatever you like)
- Set it to **Public**
- Check **"Add a README file"**
- Click **"Create repository"**

### 3. Upload the app files
- In your new repo, click **"Add file"** → **"Upload files"**
- Drag all 5 files from this folder into the upload area:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Scroll down, click **"Commit changes"**

### 4. Enable GitHub Pages
- Go to your repo's **Settings** tab (gear icon, top right)
- In the left sidebar, click **"Pages"**
- Under "Source", select **"Deploy from a branch"**
- Under "Branch", select **main** and **/ (root)**
- Click **"Save"**
- Wait 1–2 minutes. GitHub will show your URL:  
  `https://YOUR-USERNAME.github.io/sittas/`

### 5. Add to iPhone home screen
- Open **Safari** on your iPhone
- Go to `https://YOUR-USERNAME.github.io/sittas/`
- Tap the **Share button** (square with arrow, bottom toolbar)
- Scroll down and tap **"Add to Home Screen"**
- Name it **"Sittas"**
- Tap **"Add"**

Done! You now have a standalone app icon on your home screen.  
It opens full-screen, no browser bar, works offline after first load.

---

## Updating the app

To update, just upload the changed files to your GitHub repo  
(same drag-and-drop process). GitHub Pages auto-deploys in ~1 minute.
