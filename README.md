# Genyu Xu · 许亘昱

Independent Chinese and English academic homepages with the original design.

- Chinese: https://ennxu.com/
- English: https://ennxu.com/en/
- Sitemap: https://ennxu.com/sitemap.xml

## Maintenance

GitHub Pages publishes the main branch from the repository root. No build step or package installation is required. Keep CNAME and .nojekyll.

- index.html is the complete Chinese page.
- en/index.html is the complete English page.
- Both pages include their own styles, vector identity, portrait, metadata, and Person structured data. The data-i18n attributes identify corresponding text for maintenance; no runtime translation is needed.
- Update content in both HTML files together. Keep publication titles, citations, DOI links, and the design consistent. Update sitemap.xml lastmod only when the corresponding page content meaningfully changes.
- The language links work without JavaScript. Each page has a self-referencing canonical URL and reciprocal zh-CN/en/x-default hreflang links.
- Previously shared ?lang=en and ?lang=zh URLs redirect to the matching page when JavaScript is available, preserving other query parameters and section anchors. Language no longer depends on saved browser preferences.
- The small enhancement scripts preserve the current section when switching language, highlight navigation, and update the copyright year. All page content remains available without JavaScript.
- robots.txt allows crawling and identifies the sitemap, which lists only the two canonical pages.
