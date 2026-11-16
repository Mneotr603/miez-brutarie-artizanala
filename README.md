# Miez bakery website

Static site: `dist/index.html`, `dist/styles.css`, `dist/app.js`. No build required. Serve `dist/` over HTTP. Romanian default; `?lang=ro`, `?lang=ru`, `?lang=en` select a language. Preference persists locally where browser storage permits it.

## Pending brand assets

Freight and Brandon Grotesque licensed webfonts have not been provided. Current declarations use locally installed fonts when present and Georgia/Trebuchet fallbacks otherwise. Check Cyrillic glyph coverage before replacing them.

The two inline photos in the conversation did not expose original download files or filenames. Current photography is from this bakery's public gallery, pending replacement by the supplied originals. Do not present these as the requested uploads.

## Image sources

- `assets/miez-official-logo.png`: official Miez logo, matching the user's reference, retrieved from the existing bakery site's profile artwork: https://lh3.googleusercontent.com/a-/ALV-UjU_wl105yTOIMYhlU11DN4F0m5VkaEJDa6-luhAETn43RJk79A=s1000 . Used without redrawing or recolouring in header, footer and favicon.

- `assets/bread-display.jpg`: https://img3.restaurantguru.com/r4a9-meals-Miez-Brutarie-artizanala-Chisinau.jpg
- `assets/bakery-counter.jpg`: https://img02.restaurantguru.com/c26e-Restaurant-Miez-Brutarie-artizanala-Chisinau-meals.jpg
- `assets/bakery-story.webp`: optimized from the bakery's existing website gallery, https://lh3.googleusercontent.com/5YIY178ZhkEcJycL6UD0KqRdK_7QOkGR_PPxqI-zRqlHTVUnxa-_spwqq_IzdgvtQXvQB_tRpadp1YDA=s0
- `assets/gsap.min.js`: GSAP 3.14.2 via jsDelivr. GSAP runtime license applies separately from its MIT skill instructions: https://gsap.com/standard-license/

## Content

Five reviews are verbatim user supplied text with actual hyperlink destinations preserved. Reviewer names, prices and aggregate ratings are intentionally absent because they were not supplied. Hours follow the user's corrected Google Maps schedule. Google Maps directions use the bakery's listing CID.

## Verification

Playwright Chromium: 1440×1000, 390×844, 320×760; RO/RU/EN switching, overflow, image loading, pause, reduced motion, five original reviews, no uncaught JavaScript errors. Impeccable source detector and Web Interface Guidelines review completed; specific contrast/legibility findings fixed. Independent review findings (duplicate review links and arrow glyphs) fixed. Private deployment is for review; production brand assets still pending.
