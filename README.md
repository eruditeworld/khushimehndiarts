# Khushi Mehndi Arts — Website

A single-page, static website for Khushi Mehndi Arts, a mehndi artist in Khuldabad, Prayagraj. Built with plain HTML5, CSS3 and vanilla JavaScript — no frameworks or build step required.

## Structure

```
khushi-mehndi-arts/
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/script.js
│   └── images/
│       ├── hero/hero-mehndi.svg      (placeholder)
│       ├── about/artist.svg          (placeholder)
│       └── gallery/*.svg             (placeholders)
├── favicon/favicon.svg               (placeholder)
├── robots.txt
├── sitemap.xml
└── README.md
```

## Before going live — replace these placeholders

1. **Photos.** Every image in `assets/images/` is a demo SVG placeholder, clearly labeled "Demo Placeholder." Replace each with a real photograph, keeping the same filename (or update the `src` in `index.html`):
   - `hero/hero-mehndi.jpg` — a strong bridal mehndi hand photo for the hero section.
   - `about/artist.jpg` — a real photo of the artist at work.
   - `gallery/*.jpg` — real portfolio photos, sorted into the existing categories (bridal, traditional, arabic, engagement, details) using the `data-category` attribute on each `<figure class="gallery-item">`.

2. **Testimonials.** The three testimonial cards currently say "Client testimonial will be added here." Replace with genuine reviews once available — do not invent reviews or names.

3. **Pricing.** All pricing currently reads "Contact for Pricing." Add real prices only once confirmed by the client.

4. **Google Maps.** The map embed in the Contact section uses a generic query-based embed for the given address. For a pinpoint-accurate map, replace the `iframe` `src` with the exact embed URL from Google Maps ("Share" → "Embed a map") for this business.

5. **Social links.** Instagram and Facebook links in the footer are placeholder `#` links. Replace with the real profile URLs once available.

6. **Domain.** `canonical`, Open Graph `og:url`, and `sitemap.xml` use a placeholder domain (`khushimehndiarts.example`). Replace with the real domain before publishing.

7. **Favicon.** `favicon/favicon.svg` is a simple placeholder mark — replace with a proper logo-based favicon if the client has branding.

## Content rules followed

No years of experience, awards, client counts, follower counts, celebrity clients, media features, fake reviews, fake ratings or opening hours have been invented anywhere on the site or in the structured data. All of these should only be added once the client confirms real figures.

## WhatsApp & Call

- WhatsApp number: `917398669064` (+91 73986 69064)
- Pre-filled message: "Hello Khushi Mehndi Arts, I would like to enquire about your mehndi services. Please share the details and availability."
- Click-to-call uses `tel:+917398669064`

Both are wired into the header, hero, service cards, bridal section, booking steps, contact section, final CTA, the floating WhatsApp button, and the mobile action bar.

## Deployment

This is a static site — it can be deployed as-is to GitHub Pages, Cloudflare Pages, Netlify or Vercel with no build step.
