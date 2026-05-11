WESTCTECH WWW FINAL DOMAIN FIX

Final canonical domain:
https://www.westctech.com/

This package updates:
- sitemap.xml to use only https://www.westctech.com/ URLs
- robots.txt to point to https://www.westctech.com/sitemap.xml
- HTML canonical tags to use www URLs
- Missing viewport tags
- Old 404 template paths via vercel.json redirects:
  /edge.html -> /page.html
  /faq.html -> /page.html
  /index-2.html -> /
  /index.html -> /

Vercel domain setup should remain:
westctech.com -> 308 redirect -> www.westctech.com
www.westctech.com -> Production
