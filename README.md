# Gulf House Furniture L.L.C — demo site

| | |
|---|---|
| **Business** | Gulf House Furniture L.L.C · بيت الخليج للمفروشات ذ.م.م |
| **Category** | Furniture store / home furnishings showroom |
| **Location** | Al Rashidiya 2, Ajman, United Arab Emirates |
| **pitch_type** | site |
| **Language** | en (English-first, LTR, with Arabic accents) |
| **Build date** | 2026-08-17 |
| **Demo URL** | https://aro-software.github.io/demo-gulf-house-furniture-l-l-c/ |

Static single-page demo. No backend, no frameworks, no trackers.

## Structure

```
index.html      single page — inline CSS + JS
assets/         photography (local copies, nothing hotlinked)
```

## Sections

Hero · The Showroom (about) · Collections · Gallery (with lightbox) ·
Visit band · Hours &amp; Google Map · Contact with WhatsApp CTA · Footer

## Notes

- Art direction: editorial showroom — warm cream/sand ground, bronze-gold accents,
  Cormorant Garamond display over Jost, tuned to their actual classical/neo-baroque
  and upholstered-cream inventory.
- Mobile-first, designed at 375px. Verified zero horizontal overflow from 320px
  to 1920px; all tap targets ≥ 44px.
- Motion: IntersectionObserver scroll-reveal, sticky header condense, gallery hover
  zoom, lightbox. `prefers-reduced-motion` neutralises all of it. Hidden initial
  states are scoped to `.js`, so the page is fully readable with JavaScript off.
- Photography is the business's own pre-screened Google Places set. The daytime
  signage frame is deskewed and cropped above the sign's contact strip so only the
  WhatsApp number in the brief is presented as a contact route.

---

Demo by ARO Solutions.
