# 🥚 Egg Runner

**Don't crack under pressure!** An infinite runner where you guide a brave little egg through an endless obstacle course.

**Play now:** [benlambm.github.io/egg-runner](https://benlambm.github.io/egg-runner/) 🍳

## 🎮 How to Play (Mobile)

- **Swipe left / right** — dodge obstacles
- **Swipe up** — jump over flat objects
- Survive as long as you can and unlock hats along the way 🎩🥚

## 📲 Install on Your Phone

This is a full **Progressive Web App** — no app store needed.

**iPhone / iPad:**
1. Open the link in **Safari**
2. Tap the **Share** icon (box with arrow)
3. Tap **"Add to Home Screen"**

**Android:**
1. Open the link in **Chrome**
2. Tap the install banner, or Menu (⋮) → **"Add to Home Screen"**

The egg icon lands right on your home screen next to your other apps. Launches fullscreen, works offline after first load. 🥚✨

## 🏗️ Zero Dependencies, Instant Ship

This entire installable mobile app is **four files**: `index.html`, `manifest.json`, `sw.js`, and two icons. That's it. No React, no Webpack, no node_modules black hole, no build step. Pure vanilla HTML/CSS/JS.

Deployment is handled by the included GitHub Actions workflow whenever `main` changes. From `git push` to live mobile app in under 60 seconds. One branch, one workflow, zero build config. 🥚🚀

The service worker caches everything for offline play. The manifest makes it installable. The `<meta>` tags handle iOS quirks. Ship it and forget it.

## 🕰️ Two Games, One Year of AI Progress

This game was first committed on March 21, 2026, as a single morning's work: four files, vanilla everything, no build step. It is kept here as the "before" picture.

Its successor, [Egg Runner 2](https://github.com/benlambm/egg-runner-2) ([play it](https://benlambm.github.io/egg-runner-2/)), arrived on November 14, 2026, rebuilt from scratch out of a plain language description: modular code, a composed soundtrack, and automated players that prove the game is fair. Same author, same egg, eight months apart.

Read together, the two repos are a small fossil record of how fast AI assisted building moved in 2026: from a helpful assistant beside a hand written file, to an agent that ships a tested game from a description. The game did not change. The leverage did.

## 📄 License

**CC BY-NC 4.0** — [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/)

You are free to share and adapt this work **for non-commercial purposes only**, provided you give appropriate credit:

> **Egg Runner** by [Ben Lamb](https://github.com/benlambm) — Original author must be credited in any reuse or derivative work.
