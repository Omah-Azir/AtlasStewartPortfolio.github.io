# Atlas Stewart · Portfolio

Game UI/UX portfolio for Atlas Stewart. Live at https://omah-azir.github.io/atlasstewartportfolio.github.io/

Hand-built static site. No build step, no framework.

- `index.html`: the whole site. Home, Projects deck, About and Contact in one scroll; each case study opens full screen at its own anchor (`#nitro-guzzler`, `#chain-of-jewels`, `#noc-6000`, `#enshahtenti`, `#minecraft-project`).
- `img/`: web-optimized images.
- `llms.txt`: plain-text summary for AI tools and screeners.
- `robots.txt`, `sitemap.xml`: search engine discovery.
- `.nojekyll`: tells GitHub Pages to serve files as-is.

Content source of truth lives in the Claude "Portfolio" project (`portfolio/` docs). Update a doc there and ask Claude to rebuild.
