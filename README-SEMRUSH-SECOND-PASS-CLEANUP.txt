WESTCTECH SEMRUSH SECOND PASS CLEANUP

This package targets the remaining non-critical Semrush issues after Errors reached 0.

Fixes/targets:
- Adds lang="en" to real HTML pages.
- Adds hreflang="en" and hreflang="x-default" alternate links.
- Adds/normalizes canonical tags using https://www.westctech.com/.
- Adds crawlable SEO copy to the older low-word-count pages.
- Improves vague anchor text and adds accessible text/labels to icon/image links.
- Keeps sitemap.xml and robots.txt aligned with the final www domain.
- Keeps Vercel redirects for old template URLs.

Does not minify CSS/JS because the old site is fragile and minification may break layout.
