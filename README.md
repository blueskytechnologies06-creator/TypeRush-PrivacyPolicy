# TypeRush — Privacy Policy & app-ads.txt Site

This repository contains the official, store-compliant **Privacy Policy**, **Terms of Service**, and **app-ads.txt** web pages for **TypeRush** (iOS & Android).

---

## 📁 Files Included

- `index.html`: Responsive dark-mode landing page featuring the full Privacy Policy (GDPR, CCPA, COPPA, AdMob compliant) and Terms of Service.
- `app-ads.txt`: Official IAB Authorized Digital Sellers file for Google AdMob crawler verification.
- `ads.txt`: Standard duplicate file for generic crawlers.

---

## ⚡ How to Deploy for Free in 2 Minutes

### Option 1: GitHub Pages (Recommended — 100% Free Forever)
1. Initialize a Git repository inside this folder:
   ```bash
   cd /Users/rajzadafiya/Projects/typerush-privacy-site
   git init
   git add .
   git commit -m "Initial commit of privacy policy and app-ads.txt"
   ```
2. Create a public GitHub repository named `typerush-policy` (or your preferred name).
3. Push to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/typerush-policy.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub, go to **Settings > Pages > Source**, select `Deploy from a branch` > `main` (`/root`), and save.
5. Your site is live at: `https://<your-username>.github.io/typerush-policy/`!

### Option 2: Netlify / Vercel (Drag-and-Drop)
1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop this folder (`/Users/rajzadafiya/Projects/typerush-privacy-site`).
3. You get an instant custom URL like `https://typerush-privacy.netlify.app`.

---

## 📲 Connecting to Google Play & Apple App Store

1. **Google Play Console**:
   - Go to **App content > Privacy policy** and paste your live URL (e.g., `https://yourdomain.com`).
   - Go to **Store settings > Developer contact details > Website** and enter `https://yourdomain.com` *(This is where AdMob looks for `app-ads.txt`)*.

2. **Apple App Store Connect**:
   - Under **App Information > General Information > Privacy Policy URL**, paste `https://yourdomain.com`.
   - Under **Support URL**, paste `https://yourdomain.com`.

3. **Google AdMob Console**:
   - Once your website URL is saved on Google Play / App Store, AdMob's automated crawler will check `https://yourdomain.com/app-ads.txt` within 24–48 hours.
   - Go to **AdMob > Apps > View All Apps > app-ads.txt** to confirm verification.

