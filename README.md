# HAGO Studio website

Public studio home: https://studiohago.github.io/
Static HTML and CSS served by GitHub Pages. No build or tracking script.

- `index.html`, `studio.css`: studio introduction, games and contact.
- `site-icon.svg`: simple website icon in studio colors, not an official logo master.
- `privacy.html`, `style.css`: existing football-only privacy notice and its styles. Preserve this URL for store links; do not apply its data declarations to other games.
- `app-ads.txt`: existing publisher authorization; preserve unless the publisher configuration actually changes.
- `img/`: existing football artwork. Baseball's homepage graphic is an abstract sport motif, not gameplay or an approved in-game asset.

## Editing and ownership

The home represents the studio, not a single game's page. HQ maintains cross-game presentation. Game developers provide approved product facts and game-specific policy changes through the shared center.
The 2026-10-19 owner request authorizes studio-wide presentation with football and baseball. Baseball is limited to its name, development status and a short genre description; private builds, concept art, mechanics, dates and pricing are not published.
Do not replace the public support email with the owner's GitHub login email. Current public contact is `kokbaguni@gmail.com`.
Add new game-specific privacy notices only after that game's actual data collection is verified. Keep legacy URLs stable. Main-branch changes may publish automatically through Pages.

## Local preview

Run `python3 -m http.server 8765` here, then open http://localhost:8765/.
Check mobile/desktop layout, keyboard navigation, game-specific privacy link, contact link, image loading and unchanged app-ads.txt before publishing.
