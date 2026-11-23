# Portfolio v356 — Writing page

New **Writing** main page in the side navigation, after Projects. It features the verified Medium article “From new joiner to designing for a complex ESG product in one month” (published in The Design Loop, 7 July 2026), linking to its original URL. A separate link opens the author's Medium profile. No unreleased or invented articles are shown.

The page has an accessible, responsive editorial layout for normal light/dark and Far, far away light/dark themes, supports the site's SPA route `#writing` and the alias `writing.html`, and is indexed in the site search. Other portfolio content unchanged.

**To add articles in future:** duplicate `<article class="writing-article-card">` in `index.html` and update the title, excerpt, date, topic tags and external `href`. The featured layout can also be replaced with a series of smaller editorial rows. Existing Webflow image dependencies outside this page remain unchanged.
