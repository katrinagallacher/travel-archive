# Travel Archive

A personal travel map of where I've been, year by year — a static webpage that
shows every trip as a GitHub-contributions-style calendar. One square per day,
one grid per year; each day is coloured by the region of the world I was in, and
empty squares are days at home. Hover any square to see the trip.

**Live site:** https://USERNAME.github.io/REPO/

## Reading it

- **Colour = region.** The legend at the top maps each colour to a region
  (Baltics, Nordic, Western & Central Europe, Balkans, Eastern Europe, Russia,
  Middle East & Caucasus, Asia).
- **Multi-region trips** change colour mid-trip, per day — a journey that starts
  in one region and ends in another is shaded accordingly.
- **Weeks start on Monday.** Light and dark themes are available via the toggle
  (top-right); it follows your system preference by default.

## How it works

It's a single self-contained `index.html` — fonts load from a CDN and all CSS
and JavaScript are inlined, so there's no build step or dependencies. Hosted for
free on GitHub Pages.

To update: edit / replace `index.html` and commit. GitHub Pages redeploys within
a minute.

> Replace `USERNAME` and `REPO` in the link above with your GitHub username and
> repository name.
