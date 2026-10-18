# felaadejumo.com
Static site (plain HTML/CSS, no build step needed to run).
- `/` homepage · `/ai` AI Content Creation Playbook · `/books` · `/felasweekly` · `/about`
- Shared styles: `assets/site.css`. `tools_build.py` regenerates home/books/weekly/about pages (`python3 tools_build.py`). `ai/index.html` is hand-edited.
- To go live: set `CHECKOUT_URL` at the bottom of `ai/index.html`; replace `EMAIL@example.com`, social `#` links, covers and `[placeholders]`.
- Hosting: GitHub Pages, Netlify or Vercel. Links are root-relative (`/ai`), so serve from a domain root.
