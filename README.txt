MIZAN GITHUB PAGES — FONT FIXED EDITION
========================================

This package is ready to upload as-is.

FONT FIX INCLUDED
-----------------
- The corrected Mahmoud web font is INCLUDED in assets/fonts/.
- The site no longer uses local('Mahmoud Final').
- The browser is forced to use the bundled web font, not a font installed on the visitor's PC.
- WOFF2 is the primary format (small and browser-friendly), with TTF fallback.
- The web font was reduced to Arabic/Latin/numbers/punctuation while preserving OpenType shaping tables.
- Invalid/unneeded vertical metrics tables from the merged source were removed before web-font generation.
- CSS links have a cache-busting version query.

PUBLIC PATHS PRESERVED
----------------------
- Home: /
- Privacy Policy: /privacy-policy/
- Support email: acc.mahmoudgharib@gmail.com

UPLOAD TO GITHUB
----------------
Replace the files in the repository root with the contents of this folder, preserving the folder structure.
Do NOT omit assets/fonts/.
After GitHub Pages finishes deploying, open the site and press Ctrl+Shift+R (or Ctrl+F5) once.
