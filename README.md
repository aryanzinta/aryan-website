# Aryan Zinta — Personal Site

A single-page "editorial / front-page" site positioning Aryan Zinta as a Meta creative strategist for **skincare & beauty brands**. Built to pass the storefront test: *find you → believe you → book you → pay you.*

## Files
```
aryan-website/
├── index.html          ← the whole site (HTML + CSS + JS inline)
└── assets/
    ├── aryan-hero.jpg          hero portrait
    ├── aryan-about.jpg         about portrait + video poster
    ├── work-01 … work-11.jpg   the 11 ad concepts (portfolio)
    └── video-testimonial.mp4   embedded video testimonial (~46 MB)
```

## How to put it live (Netlify — the way from class)
1. Go to https://app.netlify.com/drop
2. Drag the **entire `aryan-website` folder** onto the page.
3. It's live in seconds on a `*.netlify.app` URL.
4. To use your own domain (`aryanzinta.com`): Netlify → Site settings → Domain management → add domain, then follow the DNS steps.

To edit anything later, open `index.html` and change the text, or ask Claude "change X to Y."

## Before you publish — 3 things to check
1. **Email** — the footer links to `aryan@aryanzinta.com`. If that mailbox isn't set up yet, either create it (Google Workspace on your domain) or change it to your current email in `index.html` (search for `aryan@aryanzinta.com`, two places).
2. **Video testimonial** — `assets/video-testimonial.mp4` is your LinkedIn video. Confirm you're happy publishing it. At ~46 MB it's heavy for mobile; consider hosting it on YouTube/Vimeo and embedding instead, or compressing it.
3. **Calendly** — all "Book a call" buttons point to `https://calendly.com/aryan-emails79/new-meeting`. Swap if you change links.

## The copy (all editable in index.html)
- **Headline / offer ladder / process** come straight from your own planning doc.
- **Offer:** Static Ad Sprint ($300–500) → Creative Engine retainer ($5K–8K/mo) → Scale Add-Ons.
- **Testimonials** are labeled honestly (LinkedIn recommendation / mentor feedback / peer review).

## Type & color (design system)
- Display: **Anton** · Body/quotes: **Newsreader** · Labels/data: **Space Mono**
- Ink `#0C0C0E` · Paper `#F2ECE0` · Press-red `#E4141B` · Gold `#C9A24B`
