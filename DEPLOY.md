# Share your facewest preview

Your app is in this folder: **facewest-preview** (one file: `index.html`).

## Option 1: Netlify Drop (no account needed, ~1 min)

1. Open **https://app.netlify.com/drop** in your browser.
2. Drag the **facewest-preview** folder (or the whole folder from Finder) onto the page.
3. Netlify will give you a link like `https://random-name-123.netlify.app`.
4. Share that link; anyone can open it and see the app.

(You can create a free Netlify account later to pick a nicer URL or update the site.)

---

## Option 2: GitHub Pages (free, good for a permanent link)

1. Create a GitHub account if you don’t have one: https://github.com.
2. Create a **new repository** (e.g. name: `facewest`). Don’t add a README.
3. On your Mac, open Terminal and run:

   ```bash
   cd /Users/ellamasingale/facewest-preview
   git init
   git add index.html
   git commit -m "facewest preview"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/facewest.git
   git push -u origin main
   ```
   (Replace `YOUR_USERNAME` with your GitHub username.)

4. On GitHub: **Settings** → **Pages** → under “Source” choose **main** → Save.
5. After a minute, your site will be at:  
   **https://YOUR_USERNAME.github.io/facewest/**

---

## Option 3: Run locally and share on the same WiFi

If others are on the same Wi‑Fi as you:

1. Open Terminal.
2. Run:
   ```bash
   cd /Users/ellamasingale/facewest-preview
   python3 -m http.server 8080
   ```
3. On your Mac, find your IP: **System Settings** → **Network** → your connection → IP address (e.g. `192.168.1.5`).
4. On another device (phone, friend’s laptop), open: **http://YOUR_IP:8080**  
   (e.g. `http://192.168.1.5:8080`).

---

**Recommendation:** Use **Option 1 (Netlify Drop)** for the fastest shareable link.
