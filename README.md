# Elmo Rivadeneira — The Science of Innocence (Hub Site)

A brand-new, single-page hub for the case of Elmo Rivadeneira: the buried lab
report, the science of touch DNA transfer, the real culprits, and the federal
habeas case pending today — with links out to his full pages.

**This is a NEW, separate repository.** It does not modify, replace, or attach
to any existing site (elmorivadeneira.com, the Neocities pages, or the Google
Sites hubs). The existing custom-domain site is untouched: do **not** add a
CNAME file or a custom domain to this repo.

## Files

- `index.html` — the whole site (one page, no JavaScript of its own)
- `style.css` — bright, high-contrast, phone-first styling
- `sitemap.xml`, `robots.txt` — for Google Search Console
- `404.html` — redirects any missing page back to the home page

## How to publish (GitHub Pages, from the repo root)

1. Create a **new** GitHub repository (suggested name: `science-of-innocence`).
2. Upload all of these files to the repository root (keep the names exactly).
3. In the repo: **Settings → Pages → Build and deployment → Deploy from a
   branch**, choose the `main` branch and `/ (root)`, and save.
4. GitHub publishes it at `https://<your-username>.github.io/science-of-innocence/`.
5. After it is live, update the address in three places so they match the real
   one: the `<loc>` in `sitemap.xml`, the `Sitemap:` line in `robots.txt`, and
   the canonical / `og:url` links in `index.html`.
6. In Google Search Console, add the site and submit `sitemap.xml`.

## Suggested repository description

> Elmo Rivadeneira — The Science of Innocence: the buried lab report, touch
> DNA transfer, the real culprits, and the federal habeas case (Rivadeneira v.
> Gramp, D.N.J. No. 2:21-cv-01455).

## Notes

- Plain HTML/CSS only — no Jekyll, no build step, no external dependencies
  except the embedded YouTube video.
- Nothing here changes the existing pages; this hub links to them.
