# Phineas and Ferb — Summer Collector 2

A fan-made 100-pack / 1,000-card collector game. Static site — no server, build step, database or account required.

## Files

- `index.html` — page structure
- `styles.css` — all visual styling
- `game.js` — game logic, cards, packs, trivia and languages

Keep these three files together in the same folder.

## Publish with GitHub Pages

1. Create a **public** repository on GitHub (for example `phineas-ferb-collector`).
2. Upload `index.html`, `styles.css` and `game.js` to the **root** of the repository.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Choose branch **main** and folder **/ (root)**, then **Save**.
7. Wait 1–2 minutes. Your game will be at:

   `https://YOUR-USERNAME.github.io/YOUR-REPO/`

   If the repository is named `YOUR-USERNAME.github.io`, the URL is:

   `https://YOUR-USERNAME.github.io/`

HTTPS is automatic. A private repository requires GitHub Pro to use Pages.

To update the game later, replace the three files and commit again; Pages redeploys automatically.

## Languages

Use the globe button in the top-right corner. Ten interface languages:

English, 中文, Español, Italiano, Français, 日本語, Deutsch, Português, 한국어, Русский

The interface, navigation and pack names are translated. Card names and the 110 trivia questions/answers remain in English so character names and answers stay consistent.

## Notes

- Progress saves in the browser's localStorage for the URL you use. A different domain or path is a different save.
- Coins are earned only while the game tab is open and visible. Closing it stops income but keeps the account.
- Upgrade timers keep counting down while the tab is closed.
- The Top 10 rivals are simulated locally; no server is used.
- Fan-made project. Not affiliated with Disney.
