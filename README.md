# EK Van Services — Website

Static website for **EK Van Services**, hosted on GitHub Pages.

**Live site:** [https://ekvanservices.co.uk](https://ekvanservices.co.uk)

---

## 📁 File Structure

```
ekvanservices/
├── index.html      # Main page (SEO, Schema.org, Open Graph)
├── 404.html        # Custom not-found page
├── sitemap.xml     # XML sitemap for search engines
├── robots.txt      # Crawler directives
├── llms.txt        # AI/LLM context file
├── .gitignore      # Git ignore rules
└── README.md       # This file
```

---

## 🚀 Deploying to GitHub Pages

1. Create a repository named `ekvanservices.co.uk` (or any name).
2. Push all files to the `main` branch.
3. Go to **Settings → Pages**.
4. Set **Source** to `Deploy from a branch` → `main` → `/ (root)`.
5. Add your custom domain `ekvanservices.co.uk` under **Custom domain**.
6. Enable **Enforce HTTPS** once DNS propagates.

### DNS Setup (at your registrar)

| Type  | Host | Value                   |
|-------|------|-------------------------|
| A     | @    | 185.199.108.153         |
| A     | @    | 185.199.109.153         |
| A     | @    | 185.199.110.153         |
| A     | @    | 185.199.111.153         |
| CNAME | www  | your-username.github.io |

---

## 🔍 SEO Checklist

- [x] `<title>` and `<meta name="description">` on all pages
- [x] `<link rel="canonical">` on all pages
- [x] Open Graph tags (og:title, og:description, og:image, og:url)
- [x] Twitter Card tags
- [x] Schema.org `LocalBusiness` JSON-LD
- [x] Geo meta tags (region, placename)
- [x] `robots.txt` with Sitemap reference
- [x] `sitemap.xml`
- [x] `llms.txt` for AI indexing
- [ ] Add `og-image.jpg` (1200×630px) to root — **action required**
- [ ] Add `favicon.ico` / `apple-touch-icon.png` — **action required**

---

## 🖼️ Assets To Add

Replace the placeholders below with real files before going live:

| File               | Size        | Notes                        |
|--------------------|-------------|------------------------------|
| `og-image.jpg`     | 1200 × 630  | Social share preview image   |
| `favicon.ico`      | 32 × 32     | Browser tab icon             |
| `apple-touch-icon.png` | 180 × 180 | iOS home screen icon      |

---

## 📞 Business Info

| Field   | Value                  |
|---------|------------------------|
| Name    | EK Van Services        |
| Phone   | 07832 655209           |
| Area    | East Kilbride, Glasgow |
| Domain  | ekvanservices.co.uk    |

---

## 🛠️ Maintenance

- Update `sitemap.xml` `<lastmod>` date after any content change.
- No build step required — pure HTML/CSS/JS, deploys instantly.
