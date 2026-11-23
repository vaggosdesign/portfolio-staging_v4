# Portfolio v361 — standalone content edition

Based on v360 Project Style Writing. Extract the ZIP and open index.html, or upload its contents to your existing staging repository. Preserve the assets folder structure.

- All 65 formerly remote Webflow media URLs replaced with bundled local files across index.html and the case study template. No Webflow downloader or external fallback remains.
- Existing content, styling, navigation and themes retained. The Supply Chain Visibility hero now uses the uploaded animated laptop mockup (91 frames), and the linear proof of concept uses the supplied stepper GIF rather than the duplicated tree-list GIF.
- The Hotjar screenshot uses the uploaded equivalent under a different original asset identifier. The early bnbme Airbnb/Booking.com/hybrid concept image was not supplied under its exact original ID; the uploaded Group 423 landing/search/details design concepts image is used instead. The two originally static substitutes were superseded in v362 with the original animated GIFs (241 and 143 frames).
- Additional uploaded media is retained in assets/additional without adding new page sections. Existing local videos and article covers retained.
- The contact page's Google Maps embed and external article/social/product links are unchanged and may require internet access. No Webflow dependency remains in the HTML.
- Static checks: all 65 targets exist, image files decode/validate, and all direct local asset paths resolved. Browser automation was attempted but blocked by the environment (ERR_BLOCKED_BY_ADMINISTRATOR); visual, navigation, theme, video playback and contact testing remain for staging.
- asset-migration-report.json lists exact source matches, alternate files, formats, frame counts and hashes.
