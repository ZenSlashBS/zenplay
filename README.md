# ⚡ ZenPlay — Free Browser Games Arcade

A fast, zero-cost games portal with **300+ HTML5 games** (action, puzzle, racing, .io, 2-player and more), hosted free on GitHub Pages.

**Live site:** https://zenslashbs.github.io/zenplay/

## How it works

- Games are loaded at runtime from the **GamePix publisher feed** — a licensed catalog that's legal to embed and pays revenue share. New games appear automatically; you never upload game files.
- The whole site is one `index.html` — no build step, no server, no cost.
- Search, category filters, lazy-loaded thumbnails, mobile-friendly fullscreen player.

## 💰 Turn on earnings (2 settings in `index.html`)

1. **GamePix revenue share** — register free at [partners.gamepix.com](https://partners.gamepix.com), get your Site ID (SID), and replace:
   ```js
   const SID = "1"; // ← your SID here
   ```
   With `sid=1` (demo) games work but **you earn nothing** — getting your own SID is step one.
2. **Google AdSense** (optional, apply once you have steady traffic):
   ```js
   const ADSENSE_CLIENT = "ca-pub-XXXXXXXXXXXXXXXX";
   ```

## 🚀 Enable GitHub Pages (one time)

Repo **Settings → Pages → Branch: `main` / (root) → Save**. The site goes live at the URL above in ~1 minute.

## Growing it

- Post 15–30s gameplay clips (Shorts/Reels/TikTok) linking to the site.
- Pick a niche angle (2-player games, unblocked-style, Hindi audience) and double down.
- Later: move to a custom domain (~₹800/yr) — required for AdSense approval in most cases and better for SEO.

## Credits

Games © their respective developers, distributed via the [GamePix](https://partners.gamepix.com) publisher program. ZenPlay is not affiliated with GamePix.
