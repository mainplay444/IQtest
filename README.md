# IQ NOVA — Logic Challenge

A responsive, dark-themed logic quiz website, split into separate HTML, CSS, and JavaScript files.

## Files
- `index.html` — page structure and metadata
- `style.css` — responsive visual design and animations
- `script.js` — quiz logic, translations, timer, sharing, and local records

## Features
- 12 logic and number-pattern questions
- Russian, German, Ukrainian, and English interface
- Responsive layout for phones, tablets, and computers
- Timer and progress indicator
- Share result via native sharing or clipboard fallback
- Top 10 records saved locally in the current browser
- Reduced-motion support for accessibility
- No external libraries and no paid services required

## Test locally
Keep all three files in the same folder and open `index.html` in a modern browser.

## Publish on GitHub Pages
1. Create a public repository on GitHub, e.g. `iq-nova`.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Open the published URL shown on the Pages settings screen. It usually looks like:
   `https://YOUR-USERNAME.github.io/iq-nova/`

## Important limitations
- This is an entertainment logic quiz, not a standardized IQ test or clinical assessment.
- The score is the number of correct answers out of 12, not an IQ value.
- Records are stored in local browser storage and are not shared across visitors or devices.
- A shared global leaderboard requires a backend/database.
