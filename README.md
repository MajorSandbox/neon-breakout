# neon-breakout
NEON Breakout mobile / web app

-=#=- vibe coded with A.I. (Claude, Gemini and ChatGPT) -=#=-

An arcade-style, fast-paced Breakout clone built entirely using standard web technologies. It is fully responsive, optimized for both desktop and mobile screens, and ready to be installed directly on your device.

🚀 **[Play the Game Live Here!](https://majorsandbox.github.io/neon-breakout/)**

---

## 📱 Progressive Web App (PWA) Ready

This game can be installed as a standalone Web App via your browser on desktop or smartphones—**no App Store or Google Play Store required.**

*   **Android (Chrome):** Tap the three vertical dots in the top right corner and select **"Install app"** or **"Add to Home screen"**.
*   **iOS / iPhone (Safari):** Tap the **Share** button, scroll down, and select **"Add to Home Screen"**.
*   **Desktop (Chrome/Edge):** Click the install monitor icon inside the address bar next to the bookmark star.

---

## ✨ Features

*   🕹️ **Pure HTML5 Canvas Architecture:** Lightweight, dependency-free rendering running smoothly at up to 120 FPS.
*   ***[upcoming]*** ⏱️ **Delta-Time Physics Engine:** Gameplay physics are bound to real-time milliseconds rather than frame rates. The ball flies at the exact same speed on a 60Hz desktop monitor as it does on a modern 120Hz/140Hz smartphone display.
*   💥 **Neon Particle System:** Retro-futuristic Cyberpunk/Synthwave visual style featuring glowing brick explosions, dynamic combo text popups, and fluid animation rendering layers.
*   🔋 **5 Unique Power-Up Drops:**
    *   🧲 **Sticky Paddle:** Catch the ball and launch it strategically when you are ready.
    *   🍒 **Multi-Ball Chaos:** Instantly triplicates every active ball on the screen.
    *   📏 **Paddle Expand:** Increases your defensive surface area.
    *   ❤️ **Extra Life:** Replenishes your heart pool.
    *   💎 **Special Modifications:** High-score combo multipliers and speed alterations.
*   💾 **Local Leaderboard:** Saves your scores, reached levels, and achievements directly inside the browser's secure `localStorage`.
*   🛡️ **Fair-Play Cheat Engine:** Includes specialized testing cheat states. If modifiers are used to bypass a level, highscore entries are automatically watermarked with an asterisk (`*`) to ensure the global leaderboard remains fair.

---

## 🛠️ Technology Stack

*   **Frontend Architecture:** Vanilla JavaScript (ES6+), HTML5, Canvas 2D API.
*   ***[upcoming]*** **Styles & Layout:** Responsive CSS Grid/Flexbox with safe-area styling adjustments for ultra-narrow mobile viewports (e.g., modern 20:9 screens).
*   **PWA Assets:** Modern Web App Manifest (`manifest.json`) and a dedicated Service Worker caching layer (`sw.js`) for offline stability and fluid mobile transitions.

---

## 📦 Local Installation & Development

To test or modify the source code locally on your machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/MajorSandbox/neon-breakout.git
   ```
2. Open the project directory.
3. Simply double-click `index.html` to play directly in your browser, or spin up a local server to test the PWA features:
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   ```
4. Navigate to `http://localhost:8000` in your web browser.

---

## 🤝 Contribution

Feel free to fork this project, submit issues, or open pull requests if you want to contribute new level layouts, tweak particle velocities, or introduce fresh power-ups!
