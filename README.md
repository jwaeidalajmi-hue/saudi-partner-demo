# Saudi Partner 2.0: clickable prototype

Static prototype of the Saudi Partner portal with four role journeys (Supplier, Buyer, DMO, STA). All data is sample data.

Start page: `index.html` (opens the demo launcher).

## Publish on GitHub Pages

1. Upload every file and folder in this directory to the root of the repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Notes

- `support.js` is the page runtime that renders the `.dc.html` screens. Keep it next to them.
- Images and fonts are in `assets/`. The Rihla fam trip planner is in `rihla/`.
- Pages carry a `noindex` tag so search engines skip them, but anyone with the link can open the site.
