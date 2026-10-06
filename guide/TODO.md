# Guide page – what's left

`guide/index.html` is the English "Getting started with Bestli" page (8 steps, screenshots in
`assets/guide/`). Every menu name in it was checked against the iOS app on 2026-10-06. It is on the
`guide-draft` branch so nothing goes live until it's merged into `main`.

To finish:
1. Translate into the other 31 site languages as `guide/<code>/index.html`, using the same codes as
   `privacy/` and `terms/`. Serbian stays in Cyrillic, like the rest of the site. Use the menu names
   as the app shows them in each language (iOS `*.lproj/Localizable.strings`).
2. Add the language picker to the toolbar, as on the privacy and terms pages.
3. Link the guide from the home page (navigation, and "For businesses").
4. Merge into `main`. GitHub Pages publishes it within a minute or two.

Delete this file before merging.
