# ANJ Publications — indianlawbooks.in
## GitHub Pages Deployment Guide

### Files to upload to your GitHub repo:
- `index.html` — Main website
- `sitemap.xml` — For Google Search Console
- `robots.txt` — Tells Google to index everything
- `og-image.png` — Link preview image (see below)

---

## Step 1: Create og-image.png (IMPORTANT for WhatsApp previews)

Open `index.html` in Chrome browser, open DevTools Console (F12),
and run this command to download the OG image:

```javascript
var c = document.getElementById('og-canvas');
var a = document.createElement('a');
a.href = c.toDataURL('image/png');
a.download = 'og-image.png';
a.click();
```

Upload the downloaded `og-image.png` to your GitHub repo root.

---

## Step 2: GitHub Pages Setup
1. Go to your GitHub repo → Settings → Pages
2. Source: Deploy from branch → main → / (root)
3. Save. Your site will be live at https://www.indianlawbooks.in in ~2 mins.

---

## Step 3: Google Search Console (DO THIS — critical for ranking)
1. Go to https://search.google.com/search-console
2. Add property → URL prefix → https://www.indianlawbooks.in
3. Verify via HTML file (download and upload to repo)
4. Go to Sitemaps → Add sitemap → https://www.indianlawbooks.in/sitemap.xml
5. Submit and wait 24-48 hours for Google to crawl

---

## Step 4: Google Business Profile (FREE — boosts local search)
1. Go to https://business.google.com
2. Search for "ANJ Publications Jaipur" — claim your existing listing
3. Add: photos, description, WhatsApp number, website URL
4. This makes you appear in "AIBE books Jaipur" local searches with map

---

## Step 5: Free Backlinks (boosts ranking fast)
- List on Justdial: https://www.justdial.com
- List on IndiaMart: https://www.indiamart.com
- List on Sulekha: https://www.sulekha.com
- Post in Facebook groups: "AIBE preparation", "Law students India"
- Share link on WhatsApp groups for law students

---

## SEO Keywords Already Optimised In Site:
- "AIBE bare act set 2026"
- "AIBE books Jaipur"
- "all india bar examination books"
- "AIBE diglot edition"
- "bare act set 22 books"
- "AIBE solved papers"
- "ANJ publications"
- "law books jaipur"
- "AIBE hindi english books"
- "द्विभाषी बेयर एक्ट सेट"
