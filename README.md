# namyeH Studios site

Official site for [namyeH Studios](https://namyeh.com) and our first game, **Swarmfall: Extract or Die** — a dark wave-survival extraction shooter for Android.

Live at [namyeh.com](https://namyeh.com), hosted free on GitHub Pages.

## Structure

```
index.html      Home
about.html      About the studio
privacy.html    Privacy policy (required for the Google Play listing)
contact.html    Support / business contact
styles.css      Shared styles for all pages
assets/         Images (app icon, etc.)
CNAME           Custom domain config (namyeh.com)
```

Plain static HTML/CSS — no build step, no framework. Edit a file, commit, and GitHub Pages redeploys automatically in a minute or two.

The shared stylesheet drives the responsive navigation, game landing page,
support pages, and privacy policy. Production screenshots in `assets/` are
optimized WebP copies used by the hero and gameplay gallery.

## Restore point

The original 2026 site design is preserved at the Git tag:

```
checkpoint-pre-website-overhaul-2026-08-08
```

## Local preview

Just open `index.html` directly in a browser, or serve the folder with any static file server.
