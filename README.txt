Khajra Model Rocketry website
==============================

This is a static site: no build step, no server code.

Files
  index.html        the whole site (home page plus the Team, Join, Contact and Sponsor views)
  khajra-hero.mp4   hero background video
  khajra-hero.jpg   hero poster image
  khajra-logo.png   logo

How to host it
  Keep all four files together in the same folder, then upload that folder to any static host:
  - Netlify: drag the folder onto app.netlify.com/drop
  - GitHub Pages: put the files in a repo, then Settings > Pages > deploy from the main branch
  - UMich student web hosting or any web server: copy the files into the web root

Notes
  - The 3D rockets load three.js from cdnjs.cloudflare.com and fonts from Google Fonts, so visitors need internet access.
  - The menu pages use the URL hash (#team, #join-us, #contact-us, #sponsor-us), so no server routing is needed.
  - To edit text, open index.html in any editor and search for the words you want to change.
