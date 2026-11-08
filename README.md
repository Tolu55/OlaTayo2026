# Ola & Tayo wedding website

Static site for Olamide Jumoke & Toluwani Temitayo, Saturday 14 November 2026.
No build step. `index.html` is the whole site.

## Add the photos
Put files in `photos/`: `photo-01.jpg` to `photo-09.jpg` (photo-01 is the hero) and `share.jpg` (1200x630, link preview).
Missing photos are skipped automatically, so the site works before they are added.

## Deploy on Netlify
1. Push this folder to a GitHub repository.
2. Netlify > Add new site > Import an existing project > GitHub > pick the repo.
3. Build command: leave empty. Publish directory: `.`
4. Deploy, then Site configuration > Change site name (for example `olatayo2026`).
5. If the address is not `olatayo2026.netlify.app`, update the two `og:` address lines in `index.html`.

The page asks search engines not to index it (`noindex`), because it contains bank account details.
