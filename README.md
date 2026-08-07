# Zenoir — Luxury Perfume Landing Page

A premium, mobile-friendly landing page for the Zenoir fragrance house, featuring the Yaqeen, Asmari, and Violet Zamani signatures.

## Structure
```
zenoir/
├── index.html      # the full landing page (HTML + CSS + JS in one file)
├── images/         # banner + product photos
└── README.md
```

## View locally
Just open `index.html` in any browser — no build step, no dependencies.

## Host it free on GitHub Pages
1. Create a new repository on GitHub (e.g. `zenoir`).
2. Upload every file in this folder, keeping the `images/` folder intact.
3. In the repo, go to **Settings → Pages**.
4. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
5. After a minute your site is live at:
   `https://<your-username>.github.io/zenoir/`

## Adding your logo
The page shows the "ZENOIR" wordmark by default. To use a logo image instead:
1. Save your logo as `logo.png` inside the `images/` folder.
2. That's it — the page automatically swaps the wordmark for your logo in both the header and footer. No code changes needed.

For best results use a transparent PNG (or SVG named `logo.png`) with light/gold artwork, since it sits on a dark background.

## Notes
- Built with system fonts + Google Fonts (Cormorant Garamond & Jost).
- Responsive down to small phones; respects reduced-motion preferences.
- Product **Buy Now** buttons link to alhajisperfumes.com and open in a new tab.
- Contact email: orientaloudonline@gmail.com
- Newsletter form is front-end only — connect it to your email provider (Mailchimp, Formspree, etc.) when ready.
