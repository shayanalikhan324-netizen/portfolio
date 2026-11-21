# Shayan Ali Khan — Portfolio

A personal portfolio website for **Shayan Ali Khan** — aspiring SEO professional,
digital marketing enthusiast and Computer Science student at Virtual University of Pakistan.

Built from scratch with plain HTML, CSS and JavaScript. No frameworks, no build step.

## Live site

Once GitHub Pages is enabled: `https://shayanalikhan324-netizen.github.io/portfolio/`

## Sections

- **Hero** — introduction, role typing animation, contact shortcuts
- **About** — background, learning approach, key stats
- **Experience** — timeline of professional roles
- **SEO Journey** — the "Learn SEO Today" blog and its published articles
- **Skills** — SEO, marketing and operational skills
- **Education** — degree, intermediate, and certifications
- **Contact** — email, phone, blog and location

## Files

```
index.html      Page markup + metadata + JSON-LD structured data
styles.css      Design system, layout, themes, responsive rules
script.js       Theme toggle, mobile nav, scroll reveal, counters, typing effect
favicon.svg     Site icon
robots.txt      Crawler directives
sitemap.xml     Sitemap for search engines
```

## Features

- Responsive layout (mobile, tablet, desktop)
- Light / dark theme with saved preference
- Scroll-reveal animations and animated counters
- Accessible: skip link, focus styles, ARIA labels, reduced-motion support
- SEO-ready: meta + Open Graph tags, canonical URL, JSON-LD `Person` schema,
  sitemap and robots.txt
- Lighthouse: 100 Accessibility, 100 Best Practices, 100 SEO

## Local development

Open `index.html` directly, or serve the folder:

```bash
python -m http.server 8765
```

Then visit <http://127.0.0.1:8765/>.

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and the `/ (root)` folder, then save.

The site goes live at `https://<username>.github.io/portfolio/` within a minute or two.

## Editing content

All text lives in `index.html`. Colours, spacing and fonts are defined as CSS
variables at the top of `styles.css`. If you deploy under a different URL, update
the canonical URL, Open Graph URL, `sitemap.xml` and `robots.txt`.
