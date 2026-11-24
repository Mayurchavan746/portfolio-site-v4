ARJUN DESHMUKH PORTFOLIO (dummy content): TIRANGA THEME, PROFESSIONAL VISUALS

HOW TO OPEN
1. Unzip and keep this structure: index.html, about.html, portfolio.html, resources.html, css/ (style.css + patterns.css), js/main.js, images/
2. Double-click index.html (or copy the folder to htdocs / localhost).
3. Internet is needed for Google Fonts and Font Awesome icons (and for the optional stock photos, see below).

IMAGES (nothing can show broken)
- Every image has a built-in professional vector version in images/ (tricolour gradients, line icons, neutral portrait silhouettes, Ashoka-chakra motif). These always load.
- Optional stock photos: js/main.js (top of the file) has  const PHOTOS = true;  A stock photo replaces its vector ONLY if it loads, so a dead link never shows a broken image.
  Set PHOTOS = false to use the vector art only.
- Your own photos: replace the matching file in images/ (keep the name, or change the name in the HTML). Portraits (leader.svg, leader2.svg) work best as a normal rectangular photo (3:4, face in the upper half); every portrait frame crops from the top, so no cut-out is needed.

COLOURS (tiranga)
- Saffron #FF9933, green #138808, navy (chakra) #0A2A66, white. Edit the :root tokens at the top of css/style.css.
