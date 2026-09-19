PRIORITY LEXUS VIRGINIA BEACH — L/CERTIFIED LANDING PAGE
CURRENT VERSION: 3

FILES
1. index.html — the complete standalone landing page for GitHub Pages.
2. lcertified-hero.jpg — the optimized hero image. Keep it in the same folder as index.html unless you replace the image path.

INSTALLATION
1. Upload index.html and lcertified-hero.jpg to the root of the GitHub Pages repository.
2. Keep both files beside one another.
3. If the image will not remain beside index.html, open index.html and replace this value near the beginning:
   --lc-hero-url: url('lcertified-hero.jpg');
   with the full uploaded image URL.
4. Commit and publish the files through GitHub Pages.

NOTES
- The file is now a complete HTML document with the mobile viewport settings required by GitHub Pages.
- Landing-page CSS remains scoped beneath #lc-page.
- All JavaScript is self-contained and runs only inside the landing page.
- Inventory and phone links are already connected.
- The page is responsive and includes reduced-motion and keyboard-accessibility support.

VERSION HISTORY

Version 3
- Converted index.html from a body-only fragment into a complete standalone HTML document for GitHub Pages.
- Added the missing mobile viewport declaration so phones use their real screen width and activate the intended responsive breakpoints.
- Added the HTML5 document type, language, character encoding, page title, description, theme color and favicon.
- Removed the browser’s default body margin that was creating a white border around the live page.
- Added document-level horizontal-overflow protection.
- Added min-width safeguards to every responsive grid child to prevent content from forcing the page wider than the screen.
- Made the L/Certified sub-navigation sticky for easier mobile access.
- Added button-width and long-address wrapping safeguards.
- Verified the live Version 2 page and documented the missing viewport metadata as the root mobile-scaling issue.

Version 2
- Renamed the HTML file to index.html.
- Moved lcertified-hero.jpg out of the assets folder and placed it beside index.html and README.txt.
- Reworked the mobile hero so more of the vehicle image is visible before the headline and CTAs.
- Reorganized mobile program statistics into a compact three-column row.
- Converted the LexusCare benefit controls into swipeable touch cards on phones.
- Tightened mobile typography, spacing, inspection cards, FAQ controls and CTA layouts.
- Increased mobile disclaimer size and line spacing for better readability.
- Added a 390px breakpoint for smaller phones.
- Added this permanent version-history section. Add a new entry here with every future release.

Version 1
- Created the initial L/Certified landing page.
- Added the cinematic hero, 161-point inspection section, LexusCare benefit tabs, Priority difference, FAQs, calls to action and full program disclaimers.
- Added desktop, tablet and mobile layouts with keyboard and reduced-motion support.
