# Navin Kumar — Portfolio Website

Personal portfolio site for **Navin Kumar**, Lead Software Engineer & Engineering Leader. Live at [rubyonrails.tech](https://rubyonrails.tech).

---

## About

A single-page portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. Hosted on GitHub Pages with a custom domain.

**Highlights:**
- Dark theme with animated blobs and scroll-reveal effects
- Fully responsive — mobile hamburger nav with fullscreen drawer
- Sections: Hero, About, Experience, Skills, Education, Contact
- SEO-optimised with Open Graph, Twitter Card, JSON-LD structured data, sitemap, and `llms.txt` for AI crawlers

## Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, Grid, Flexbox) |
| Scripting | Vanilla JS (IntersectionObserver, scroll-spy) |
| Fonts | Bricolage Grotesque · Lora · JetBrains Mono (Google Fonts) |
| Hosting | GitHub Pages |
| Domain | Cloudflare DNS → `rubyonrails.tech` |

## Project Structure

```
.
├── index.html          # Single-page app — all content and styles inline
├── robots.txt          # Crawl directives (includes AI bots)
├── sitemap.xml         # XML sitemap for search engines
├── llms.txt            # Plain-text profile for AI assistants
├── site.webmanifest    # PWA manifest
├── favicon.svg / .ico / favicon-16.png / favicon-32.png
├── apple-touch-icon.png / icon-192.png / icon-512.png
├── og-image.png         # Social share card (Open Graph / Twitter)
└── CNAME                # Custom domain config for GitHub Pages
```

## Local Development

No build tools required. Open directly in a browser:

```bash
# Option 1 — Python
python3 -m http.server 8080

# Option 2 — Node
npx serve .

# Option 3 — VS Code
# Install the "Live Server" extension and click "Go Live"
```

Then visit `http://localhost:8080`.

## Deployment

Push to the `main` branch — GitHub Pages deploys automatically within ~30 seconds.

```bash
git add index.html robots.txt sitemap.xml llms.txt
git commit -m "Update portfolio"
git push
```

## SEO Checklist

- [x] Meta description & keywords
- [x] Canonical URL
- [x] Open Graph tags (LinkedIn, Slack, WhatsApp previews)
- [x] Twitter Card (`summary_large_image`)
- [x] JSON-LD — `Person` + `WebSite` schema
- [x] `sitemap.xml` submitted to Google Search Console
- [x] `robots.txt` with AI crawler directives
- [x] `llms.txt` for LLM/AI assistant indexing

## Contact

| | |
|---|---|
| Email | navinkumar2508@gmail.com |
| LinkedIn | [linkedin.com/in/dynamicnavin](https://linkedin.com/in/dynamicnavin) |
| GitHub | [github.com/Navin-Baliyase](https://github.com/Navin-Baliyase) |
| Phone | +91 97386 77711 |

---

© 2026 Navin Kumar
