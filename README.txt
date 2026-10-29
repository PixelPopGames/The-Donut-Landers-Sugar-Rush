THE DONUT LANDERS — NEON MATCH GAME

LATEST CHANGES
- A true 5-column by 5-row board (25 tiles total) with larger icons.
- Match any three or more identical symbols in a horizontal or vertical line. Character-order requirements have been removed.
- Explosive match animations with expanding neon rings and flying particles.
- Distinct synthesized arcade sounds for 3-, 4-, 5-tile matches and jackpot matches.
- Updated scoring: 3 in a row = 100 points per cleared tile; 4 in a row = 175 points per tile + 350 bonus; 5 in a row = 300 points per tile + 1,000 bonus. Cascades multiply points up to 3x.
- Mini Donut Show (🎰 placeholder) is deliberately rare. Matching three of the special icons awards an additional 7,777 points, multiplied by the current combo multiplier. Replace the emoji/image later without changing the scoring logic.
- Removed the Sweet 777 title and the character-order instruction. The bottom now displays only www.TheDonutLanders.com.
- Best score is saved locally when browser storage is available.

UPLOAD TO GITHUB PAGES
1. Download and unzip this package.
2. Open your game's GitHub repository.
3. Upload the CONTENTS of the Donut_Landers_Donut_Match folder into the repository root, replacing index.html, style.css, game.js and README.txt. Do not upload the ZIP itself.
4. Commit the changes to the main branch.
5. Open Settings > Pages and confirm Deploy from a branch, main, /(root).
6. Wait for deployment, then open the Pages URL and refresh.

FILES
- index.html — page structure and website footer
- style.css — neon theme, 5x5 board, large icons and explosions
- game.js — matching rules, scoring, rare 777 bonus and generated sound effects
- assets/images/ — optional image assets
- assets/music/ — optional music assets

The current symbols use emoji placeholders. Add assets/images/game-logo.png if you want a logo at the top. Music files can be added to assets/music using theme.mp3, theme-1.mp3, theme-2.mp3, theme-3.mp3 and theme-4.mp3. Browser autoplay restrictions may require a tap before music starts.

VALIDATION
JavaScript syntax was checked with Node.js. This package has not been tested in a live browser in this environment.
