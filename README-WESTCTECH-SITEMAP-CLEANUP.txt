Westctech sitemap/crawl cleanup

Prepared for canonical domain: https://www.westctech.com/

Changes included:
1. Added clean sitemap.xml with only real HTML pages, using HTTPS + WWW canonical URLs.
2. Replaced old google_sitemap.xml.gz so it no longer lists HTTP URLs, images, scripts, SWF files, or duplicate/non-canonical paths.
3. Added robots.txt pointing to https://www.westctech.com/sitemap.xml.
4. Added canonical tags to existing HTML pages.
5. Updated internal links that pointed to missing pages:
   - faq.html -> page.html
   - single.html -> page.html
   - index-2.html / index.html -> /
   - blog.html -> /
   - all_styles.html -> portfolio.html
   - edge.html -> /
6. Added Vercel redirects for old/missing duplicate URLs.
7. Removed the old redirect-to-westcoaststonework.com behavior from legacy htaccess/web.config content.

Submit this sitemap in Search Console:
https://www.westctech.com/sitemap.xml

Do not submit old non-canonical versions such as:
http://westctech.com/
https://westctech.com/
https://www.westctech.com/index.html
