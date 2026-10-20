SolarScape Solutions — website (v3)
===================================

Six pages, each one self-contained (styles, scripts, logo, posters and rendered images inside the file):
  index.html  about.html  services.html  projects.html  savings.html  contact.html

What's in it
  - SOLAR preloader (scene inside the letters, dive through the O, under 2 s) on the first visit,
    then a page curtain with the page name between pages
  - Photo-real 3D villa: physical sky, real shadows, haze, panels clink into place as you scroll, dusk lighting
  - Silver/graphite palette, light + dark themes
  - Archivo expanded / hollow outline / Instrument Serif italic headline mixes
  - Glass UI, rolling-label buttons, compact dropdown menu and compact chat tab
  - Synthesised sound effects (toggle in the nav, remembered per visitor)

DEPLOY
  Keep all six files together in one folder (no subfolders).
  Vercel: put them in a GitHub repo root, import, Framework preset "Other", no build command.
  Netlify: drag this folder onto app.netlify.com/drop.

NEEDS INTERNET
  Google Fonts, GSAP, Lenis and Three.js load from public CDNs.
  Stock photos load from Unsplash; team photos and client logos load from solarscape.pk.
  If any photo fails, a rendered fallback shows instead.

TO CONFIRM WITH THE CLIENT
  - WhatsApp number used everywhere: +92 309 2001444
  - Gulshan-e-Iqbal office address and Jinko / LONGi panel brands (from an outside directory)
  - Savings figures are estimates (~4.5 kWh per kWp per day, Rs 55 per unit, editable by visitors)
  - The live monitor on the home page is a labelled simulation
