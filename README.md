# AAAI-27 Workshop on Human-Centric Agentic Mobility Services

Website for the AAAI-27 Workshop on Human-Centric Agentic Mobility Services (Montréal, Canada, February 2027).

The site is plain HTML and CSS with no build step, so it can be served directly by GitHub Pages.

## Pages

- `index.html`: overview, topics, important dates, sponsors
- `cfp.html`: call for papers and submission instructions
- `speakers.html`: advisory chairs, invited speakers, and panelists
- `program.html`: one-day schedule
- `organizers.html`: organizing committee and contact

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
4. The site will be available at `https://<user-or-org>.github.io/<repository>/` within a few minutes.

## Updating content

Each page is self contained. To update the navigation, change the `<nav>` block in every page. Dates appear on `index.html`, `cfp.html`, and `program.html`, so update all three when a deadline changes.
