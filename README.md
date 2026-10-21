# sticker-ai-app
# 🎨 Sticker AI Studio (Android Ready)

An AI-powered animated sticker generator with procedural Web Audio API synthesis and APNG/WebM batch export.

## 🚀 Features
- **Multi-Image Batch Upload:** Animate multiple images simultaneously.
- **APNG & WebM Export:** Generate animated transparent stickers or video files.
- **Web Audio Engine:** Procedural sound generator (Pops, Chirps, Chimes, Boings).
- **Gemini Vision API Support:** Auto-analyze sticker mood and auto-assign motion styles.

## 📲 How to build for Google Play Store (TWA)
1. Push this code to GitHub.
2. Deploy via **GitHub Pages** or **Vercel** to get an HTTPS Web URL.
3. Run Bubblewrap CLI on your computer:
   ```bash
   npx @bubblewrap/cli init --manifest=https://YOUR-APP-URL/manifest.json
   npx @bubblewrap/cli build
