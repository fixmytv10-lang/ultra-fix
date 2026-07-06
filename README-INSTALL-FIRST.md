# Ultra TV Fix - Google Indexing / SEO Files

Domain used in this package:

https://ultra-tv-fix.in

## 1) Upload these files to GitHub repository root

Put these files in the same place where your `index.html` is located:

- CNAME
- .nojekyll
- robots.txt
- sitemap.xml
- site.webmanifest
- privacy.html
- terms.html
- 404.html
- favicon.ico
- icon-192.png
- icon-512.png
- og-image.jpg

## 2) Paste SEO code inside index.html

Open `head-seo-snippet.html`.

Copy all code from it and paste inside your existing `index.html` before closing `</head>`.

Do not paste it inside `<body>`.

## 3) GitHub Pages custom domain

Go to:

Settings > Pages > Custom domain

Add:

ultra-tv-fix.in

Then save.

## 4) Hostinger DNS records

A records:

@ -> 185.199.108.153  
@ -> 185.199.109.153  
@ -> 185.199.110.153  
@ -> 185.199.111.153  

CNAME:

www -> fixmytv10-lang.github.io

TTL:

Default / 14400

## 5) Check these URLs after upload

https://ultra-tv-fix.in/robots.txt  
https://ultra-tv-fix.in/sitemap.xml  
https://ultra-tv-fix.in/privacy.html  
https://ultra-tv-fix.in/terms.html  

## 6) Google Search Console

Add property:

ultra-tv-fix.in

Submit sitemap:

sitemap.xml

Full sitemap URL:

https://ultra-tv-fix.in/sitemap.xml

Then use URL Inspection for:

https://ultra-tv-fix.in/

## 7) Important

Sitemap helps Google discover URLs, but it does not guarantee instant indexing.
First indexing may take time after DNS and HTTPS are active.
