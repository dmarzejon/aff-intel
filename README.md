# Aff Intel

Static affiliate review/comparison site for **AI & productivity tools**, published via **GitHub Pages**.

**Live site (after Pages is enabled):** https://dmarzejon.github.io/aff-intel/

**Repo:** https://github.com/dmarzejon/aff-intel

## What’s included

| Path | Purpose |
|------|---------|
| `index.html` | Hub / homepage |
| `posts/` | Comparison & review articles (HTML) |
| `affiliates.md` | Affiliate link map (`#AFFILIATE:*` placeholders for Affiliate Bot) |
| `DISCLOSURE.md` | FTC affiliate disclosure |
| `assets/styles.css` | Shared dark theme |
| `sitemap.xml` / `robots.txt` | SEO crawl helpers |

Products covered (placeholders): ChatGPT Plus, Claude Pro, Notion AI, Make.com, n8n Cloud, Descript, CapCut, Midjourney, Cursor, GitHub Copilot, ConvertKit/Beehiiv, Gumroad.

## Enable GitHub Pages

1. Open **Settings → Pages** on this repository.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: **`main`** / folder: **`/ (root)`**.
4. Save. Wait 1–2 minutes, then visit:
   - https://dmarzejon.github.io/aff-intel/
5. Optional: add a custom domain under Pages → Custom domain.

No Jekyll build is required — this is plain static HTML/CSS. If GitHub ever treats underscore folders specially, a `.nojekyll` file is included so assets serve as-is.

## Affiliate Bot workflow

1. Register affiliate programs for slugs listed in `affiliates.md`.
2. Replace each `#AFFILIATE:<slug>` href with the live tracking URL (keep `rel="sponsored noopener"`).
3. Update the “Live URL” column in `affiliates.md`.
4. Redeploy is automatic on push to `main` once Pages is on.

## Local preview

```bash
# from repo root
python3 -m http.server 8080
# open http://localhost:8080
```

## FTC compliance

Every HTML page includes a visible affiliate disclosure banner linking to `DISCLOSURE.md`. Keep that banner when adding new posts.

## License

Content © site owner. Tool names and logos are trademarks of their respective owners; no affiliation or endorsement implied beyond disclosed affiliate relationships.
