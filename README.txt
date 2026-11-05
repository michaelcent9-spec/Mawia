LYNNET MAWIA — 20TH BIRTHDAY EXPERIENCE
========================================

A three-page, mobile-first birthday website made with HTML, CSS and vanilla JavaScript.

FILES
-----
index.html       Cinematic introduction
birthday.html    Birthday message and Arcane-inspired gallery
afterdark.html   Luxury automotive / After Dark finale
style.css        Shared visual system and responsive layouts
script.js        Reveal effects, birthday countdown, image fallback
favicon.svg      Local site icon
assets/          Six supplied image assets, stored locally

IMAGES
------
The supplied images have been included locally, so the website does not depend on
random image hotlinks:
- arcane-vi.jpg
- arcane-jinx.jpg
- arcane-sisters.jpg
- arcane-warrior.jpg
- car-1.jpg
- car-2.jpg

You can replace any image later by keeping the same filename and placing the new
image in assets/. The current Arcane-inspired artwork is user-provided imagery.
Check image rights before redistributing artwork publicly.

LOCAL PREVIEW
-------------
Open index.html in a browser. For the most reliable preview, run a local static
server from this folder:
  python -m http.server 8000
Then visit http://localhost:8000

GITHUB PAGES DEPLOYMENT
-----------------------
1. Create a public GitHub repository.
2. Extract this ZIP.
3. Upload the CONTENTS of the lynnet_20th_birthday folder to the repository root.
   index.html must be directly in the root, not inside another nested folder.
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for GitHub Pages to finish publishing.
8. Your site will be:
   https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/

NOTES
-----
- No backend, database, API key, or paid service is required.
- Google Fonts are optional; local fallback fonts are defined.
- The birthday countdown targets 6 November 2026, East Africa Time (UTC+3).
  After midnight on that date it displays zeroes.
- All internal links and asset paths are relative, so GitHub Pages project-site
  URLs work without a custom domain.
