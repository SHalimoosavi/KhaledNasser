# Khalid Nasser — Static Athlete Website

Canonical project URL: `https://shalimoosavi.github.io/KhaledNasser/`

## Stack
- Semantic HTML5
- CSS + minimal vanilla JavaScript
- JSON-LD / Schema.org
- No trackers, analytics, embeds or third-party JS
- Responsive, mobile-first, WCAG-oriented focus and reduced-motion support
- GitHub Pages compatible under `/KhaledNasser/`

## Push to GitHub

```bash
cd /path/to/KhaledNasser
git init
git branch -M main
git add .
git commit -m "feat: launch Khalid Nasser athlete website"
git remote add origin https://github.com/SHalimoosavi/KhaledNasser.git
git push -u origin main
```

## GitHub Pages

1. Repository → **Settings → Pages**.
2. **Deploy from a branch**.
3. Select **main** and **/ (root)**.
4. Save and wait for deployment.
5. Verify `https://shalimoosavi.github.io/KhaledNasser/`.

`.nojekyll` is included.

## Custom domain later

Do not create `CNAME` now. When the domain is chosen:

```bash
echo "example.com" > CNAME
```

Then replace the canonical base in the HTML, sitemap, robots, manifest and llms files; update Open Graph and JSON-LD URLs; configure the domain in GitHub Pages; enforce HTTPS.

## Google Search Console

1. Add the GitHub Pages URL property.
2. Choose **HTML tag** verification.
3. Place Google's verification `<meta>` tag inside `<head>` of `index.html`.
4. Deploy and verify.
5. Submit `sitemap.xml` under **Sitemaps**.
6. Inspect the homepage, `/press/` and `/faq/`.
7. Request indexing after deployment.

## Bing Webmaster Tools

1. Add the GitHub Pages URL.
2. Verify ownership.
3. Submit `https://shalimoosavi.github.io/KhaledNasser/sitemap.xml`.
4. Use URL inspection/indexing tools for the key pages.

## Post-launch checklist

- Rich Results Test
- Schema Markup Validator
- PageSpeed Insights
- Core Web Vitals after real traffic
- robots.txt and sitemap accessibility
- canonical / hreflang checks
- Open Graph preview
- Mobile UX
- BoxRec / boxing-database consistency
- LinkedIn / YouTube entity consistency
- Legitimate press coverage and backlinks
- Wikipedia/Wikidata only if independent notability and sourcing requirements are met
- Keep record/ranking data current

## Image rights

Supplied images are retained in `assets/images/`. Confirm photographer/rightsholder permissions before editorial republication. Promotional artwork may have separate rights.

## Research

See `RESEARCH.md` for the 19-site research summary and adopted design patterns.
