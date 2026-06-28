# bloomsort
Mobile Game - Sort | Stack | Bloom
<div align="center">
# 🌸 Bloom Sort
 
### A satisfying color-sorting puzzle game — free to play, runs in any browser
 
[![Live Demo](https://img.shields.io/badge/▶%20Play%20Now-Live%20Demo-fcd250?style=for-the-badge&labelColor=1b4d28)](https://yourusername.github.io/bloom-sort)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&labelColor=1b4d28)](LICENSE)
[![Made With](https://img.shields.io/badge/Made%20With-React-61dafb?style=for-the-badge&labelColor=1b4d28&logo=react)](https://react.dev)
 
<br/>
> Sort flowers by color into their matching pots.  
> Simple to learn — wonderfully tricky to master.
 
<br/>
<!-- Replace the src below with your actual screenshot paths once uploaded to the repo -->
<img src="screenshots/01_splash.svg" width="180" alt="Splash screen"/>
&nbsp;&nbsp;
<img src="screenshots/02_gameplay.svg" width="180" alt="Gameplay"/>
&nbsp;&nbsp;
<img src="screenshots/03_hint.svg" width="180" alt="Hint system"/>
&nbsp;&nbsp;
<img src="screenshots/05_win.svg" width="180" alt="Win screen"/>
</div>
---
 
## 🎮 How to Play
 
1. **Tap a pot** to pick up the flowers inside
2. **Tap another pot** to move them — only the same color can stack together
3. **Fill each pot** with 4 flowers of the same color to complete it
4. **Sort all pots** to finish the level
Use **hints** and **undos** when you're stuck. Watch a short ad to earn more.
 
---
 
## ✨ Features
 
| Feature | Details |
|---|---|
| 🌻 **20 Levels** | 4 chapters — Spring, Summer, Autumn, Winter |
| 🎯 **Star Ratings** | Earn 1–3 stars based on moves used |
| 💡 **Hint System** | Highlights a valid move when you're stuck |
| ↩ **Undo** | Walk back any move, no penalty |
| 📺 **Rewarded Ads** | Watch an optional ad to earn hints & undos |
| 💾 **Auto-save** | Progress saves automatically between sessions |
| 📱 **Mobile-first** | Designed for one-handed portrait play |
| 🌐 **No install** | Runs in any browser — no app store needed |
 
---
 
## 🚀 Play It
 
**Hosted on GitHub Pages:**
```
https://yourusername.github.io/bloom-sort
```
 
Just open the link on any device — phone, tablet, or desktop.
 
---
 
## 🛠 Tech Stack
 
- **React 18** — UI and game state
- **No dependencies** beyond React — zero external game libraries
- **localStorage** — progress and token persistence
- **AdMob-ready** — mock rewarded ads that swap cleanly for real AdMob SDK via Capacitor
---
 
## 📁 Project Structure
 
```
bloom-sort/
├── index.html              ← The entire game (single self-contained file)
├── screenshots/            ← Play Store / App Store screenshots
│   ├── 01_splash.svg
│   ├── 02_gameplay.svg
│   ├── 03_hint.svg
│   ├── 04_rewarded_ad.svg
│   └── 05_win.svg
├── config/
│   ├── AndroidManifest.xml ← Ready for Capacitor / Android build
│   └── PlayStoreListing.txt← Copy-paste text for Google Play Console
└── README.md
```
 
---
 
## 📱 Publish to App Store (optional)
 
The game is built to wrap cleanly into a native Android or iOS app using [Capacitor](https://capacitorjs.com).
 
```bash
# 1. Install Capacitor
npm install @capacitor/core @capacitor/cli @capacitor/android
 
# 2. Initialize
npx cap init "Bloom Sort" com.yourname.bloomsort --web-dir .
 
# 3. Add Android
npx cap add android
npx cap sync
 
# 4. Open in Android Studio
npx cap open android
```
 
Then replace the placeholder Ad Unit IDs in `config/AndroidManifest.xml` with your real [AdMob](https://admob.google.com) IDs.
 
---
 
## 💰 Monetization
 
Bloom Sort uses a **rewarded ad model** — the game is free, players optionally watch ads to earn in-game tokens (hints and undos). No forced ads, no paywalls.
 
**Ad trigger points:**
- Hint button with 0 hints → Watch ad → earn 3 hints
- Undo button with 0 undos → Watch ad → earn 5 undos  
- Win screen → Watch optional ad → earn bonus tokens
- Stuck modal → Watch ad → get unstuck
On web (GitHub Pages): uses mock ads for demonstration.  
On Android/iOS (Capacitor): swap in real [AdMob rewarded ads](https://developers.google.com/admob/android/rewarded).
 
---
 
## 🗺 Roadmap
 
- [ ] Add 80 more levels (target: 100 total)
- [ ] Sound effects and haptic feedback
- [ ] Daily challenge level
- [ ] Leaderboard (fastest solve per level)
- [ ] iOS App Store release
- [ ] Google Play release
- [ ] Dark / light theme toggle
---
 
## 📄 License
 
MIT — free to use, modify, and distribute.  
If you build something with it, a star ⭐ is always appreciated.
 
---
 
## 🙋 Contact
 
Built by **[Your Name]**  
Questions or feedback → open an [Issue](https://github.com/yourusername/bloom-sort/issues)
 
<div align="center">
<br/>
Made with 🌸 and React
</div>
 
