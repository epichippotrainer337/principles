SITE 1101 — Learning canvas (study pack)
========================================

WHAT'S IN THIS FOLDER
  index.html           The learning canvas. Open it in a browser.
  lessons.js           The lesson text shown inside each node (keep beside index.html).
  reading-guide.html   The full weeks 1-7 guide as one long, printable page.
  sources/             The downloaded course chapters (dark theme), their images,
                       and the two PDF slide decks.

HOW TO PUT IT ON VERCEL
  1. Unzip this folder.
  2. Go to vercel.com and sign in.
  3. Drag the unzipped folder onto the Vercel dashboard (or run `vercel` inside it
     from a terminal). Choose "Other" as the framework — no build step, no settings.
  4. Vercel serves index.html at your new address. reading-guide.html and
     sources/... work from the same folder, so keep the structure exactly as is.

NOTES
  - Everything works offline: open index.html directly from your disk.
  - Your progress ("explored" ticks) and the mistake log are saved in your browser,
    not on a server.
  - Fonts are system fonts, so nothing is fetched from the internet.
  - The raw, unstyled HTML dumps of the original course pages (-original.html) were
    left out; the cleaned, styled chapters in sources/ contain the same text.
