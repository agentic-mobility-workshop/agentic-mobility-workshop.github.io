# AAAI-27 Workshop on Human-Centric Agentic Mobility Services

Website for the AAAI-27 Workshop on Human-Centric Agentic Mobility Services (Montréal, Canada, February 2027).

Live site: https://agentic-mobility-workshop.github.io/

The site is plain HTML and CSS with no build step, so it can be served directly by GitHub Pages.

## Pages

- `index.html`: single page with About, Call for Papers summary, Speakers, Program, Organizing Team, Sponsors, and Contact. The navigation bar jumps to these sections.
- `cfp.html`: full call for papers and submission instructions.

Shared styles live in `assets/style.css`.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser.

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, and save.
4. Because the repository is named `agentic-mobility-workshop.github.io`, the site is served at the root of https://agentic-mobility-workshop.github.io/ within a few minutes.

## Updating content

Section ids on `index.html` (`about`, `cfp`, `speakers`, `program`, `team`, `sponsors`, `contact`) are used by the navigation and by links from `cfp.html`, so keep them stable. Dates appear on both `index.html` and `cfp.html`, so update both when a deadline changes.
