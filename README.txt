THE DONUT LANDERS: SWEET 777 — NEON ARCADE EDITION

WHAT'S UPDATED
- Neon pink, electric blue, purple and cyan arcade palette.
- Slowly pulsing glow around the game shell and title.
- Game tiles gently bob and shine like glossy candy bubbles.
- The Mini Donut Show tile gets a brighter animated jackpot glow.
- Buttons and score panels have neon highlights.
- Reduced-motion accessibility setting is respected.

UPLOAD TO GITHUB PAGES
1. Download and unzip this package.
2. Open your GitHub game repository.
3. Upload the CONTENTS of the unzipped folder into the repository root (not the ZIP itself and not a nested folder).
4. Commit the changes to the main branch.
5. In Settings > Pages, select Deploy from a branch, main, /(root), then Save.
6. Wait for deployment, then open the Pages URL and refresh the page.

FILES
- index.html — game page
- style.css — neon visual theme and animations
- game.js — match-3 game logic and generated sound effects
- assets/images/ — optional images
- assets/music/ — optional music files

OPTIONAL ART FILES
You can add assets/images/game-logo.png to show a logo at the top. The current board uses emoji placeholders; custom character/item image integration is a separate code update.

MUSIC
Place theme.mp3, theme-1.mp3, theme-2.mp3, theme-3.mp3 and theme-4.mp3 in assets/music/. Browser autoplay restrictions mean music may not begin until the player taps/clicks the game or sound button. The current audio implementation is a starter and does not guarantee seamless rotation through all four gameplay tracks.

NOTE
This is a visual update to the previously supplied starter game. The code was syntax-checked, but not tested in a live browser in this environment.
