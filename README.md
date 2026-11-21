# Shayan Ali Khan — Portfolio

An editorial one-page portfolio for **Shayan Ali Khan** — SEO and content for small
businesses, Computer Science student at Virtual University of Pakistan, based in Rawalpindi.

Plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

## Live site

`https://shayanalikhan324-netizen.github.io/portfolio/`

## Design approach

The page follows the [Taste Skill](https://github.com/Leonxlnx/taste-skill) rules for a
**service** page:

- Flat colour, one accent (`#17553f`), no gradients, no violet, no dark hero
- Type-led: Fraunces for display, Inter for body
- One section per screen, hero alone on the first screen
- Equal left and right content edges, everything on the `.wrap` or the grid columns
- No scroll-fade on sections. One hero entrance on load, one dealt type moment, and a
  quiet hover layer (cards lift 2px, buttons step and press, underlines draw)
- Real contact details and no invented facts, quotes or figures

## Sections

| Section | Content |
|---|---|
| Hero | Name, role, one hard fact, primary email action, key numbers |
| Experience | Four roles as a dated row list |
| Learn SEO Today | The blog, a type moment, and the six published guides |
| Capabilities | Eight capability blocks and languages |
| Education | Degree, intermediate, three certifications |
| Contact | Email, phone, blog, location |

## Files

```
index.html      Markup, metadata, JSON-LD Person schema
styles.css      Design tokens, layout, motion, responsive rules
script.js       Mobile menu, active section, the one moment, year
favicon.svg     Site icon
robots.txt      Crawler directives
sitemap.xml     Sitemap
```

## Local development

```bash
python -m http.server 8765
```

Then open <http://127.0.0.1:8765/>.

## Deploying with GitHub Pages

1. Push to GitHub.
2. **Settings → Pages**.
3. Source: **Deploy from a branch**, branch **`main`**, folder **`/ (root)`**.
4. Save. The site goes live within a minute or two.

## Editing

All copy lives in `index.html`. Colours, type and spacing are CSS variables at the top of
`styles.css`. If the site moves to another URL or domain, update the canonical URL, the
Open Graph URLs, `sitemap.xml` and `robots.txt`.
