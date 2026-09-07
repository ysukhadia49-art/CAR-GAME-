# 🏁 VELOCITY RUSH — GitHub Deployment Files

This folder contains the **ready-to-deploy** files for GitHub Pages.
All files are in this **single flat folder** with **NO subfolders**, making it 100% compatible with GitHub's web file uploader.

---

## 🚀 How to Deploy on GitHub Pages in 4 Simple Steps

### Step 1: Create a New GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Enter a repository name (for example: `velocity-rush`).
3. Set visibility to **Public**.
4. Check **"Add a README file"** (or leave unchecked).
5. Click **Create repository**.

### Step 2: Upload the Files
1. Inside your new repository, click **Add file** (top right) ➔ **Upload files**.
2. Drag and drop ALL the files from this folder directly into GitHub:
   - `index.html`
   - `index.js`
   - `index.css`
   - `standalone.html` (optional 1-file backup)
   - `.nojekyll`
3. Scroll down and click the green **Commit changes** button.

### Step 3: Enable GitHub Pages
1. In your repository, click **Settings** (top tab with gear icon).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment** ➔ **Branch**:
   - Change branch from `None` to **`main`** (or `master`).
   - Leave the folder as **`/ (root)`**.
   - Click **Save**.

### Step 4: Play Your Game Live!
1. Wait about 30–60 seconds for GitHub to build the page.
2. Refresh the **Pages** settings screen.
3. You will see a banner:
   > **"Your site is live at https://<your-username>.github.io/velocity-rush/"**
4. Click the link and enjoy **Velocity Rush** in full 3D!

---

## 📁 Files in This Folder

| File | Purpose |
|------|---------|
| `index.html` | The main game webpage and UI structure |
| `index.js` | Complete game engine (Three.js 3D renderer, BMW M5 model, 10 camera modes, race physics, sound synthesizers) |
| `index.css` | Arcade racing styles, responsive HUD, and menu styling |
| `standalone.html` | All-in-one single-file version (CSS + JS inlined directly into HTML) |
| `.nojekyll` | Tells GitHub Pages to serve all files directly without Jekyll filtering |
