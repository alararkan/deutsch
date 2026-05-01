# Deutsch lernen

A German flashcard PWA you can add to your iPhone home screen.

## Features
- Type your answer — automatically rated as correct, typo, or wrong
- Fuzzy matching tolerates small spelling mistakes
- 3 categories: Good / Medium / Bad based on your answer history
- "I don't know" button to skip and see the answer
- Randomised direction — sometimes German→English, sometimes English→German
- Works offline once installed
- Dark mode support

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `deutsch-lernen`)
2. Push all these files:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/deutsch-lernen.git
   git push -u origin main
   ```
3. Go to your repo → **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch** → `main` → `/ (root)`
5. Hit Save — your app will be live at `https://YOUR_USERNAME.github.io/deutsch-lernen`

## Add to iPhone home screen

1. Open the link above in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Give it a name and tap **Add**

Done! It now opens full screen like a native app, with your data saved locally on your phone.

## Files
```
index.html      ← the whole app
manifest.json   ← PWA metadata
sw.js           ← service worker (offline support)
icons/          ← app icons
README.md       ← this file
```
