# SWWJ Laser — Website Redesign Brief & Claude Design Prompt

## 1. Who they are (context)
**Southwest Waterjet & Laser** — a family-owned, ISO 9001:2015-certified precision contract
manufacturer in Phoenix, AZ (20+ years). They run high-end **Trumpf** lasers (flat + tube),
the **largest OMAX waterjet in Arizona**, and a **Trumpf TruBend** press brake. Tagline:
**"Understand. Deliver. Improve."** They serve engineers, OEMs, fabricators, and job-shops
who need fast, accurate cut/formed metal (and exotic materials) and quick quotes.

## 2. Audience & primary goal
- **Audience:** procurement/engineering buyers at manufacturers, contractors, makers — technical, deadline-driven, comparing job shops.
- **#1 conversion goal:** **submit an RFQ / upload a CAD file** (or call for a quote). Everything funnels here.
- Secondary: build trust (certs, equipment, capacity) and rank locally/regionally.

## 3. What's wrong with the current site (redesign targets)
- Dated WordPress/Elementor look; inconsistent typography, low visual hierarchy, generic stock feel.
- Conversion is buried — RFQ/upload should be a persistent, obvious primary action.
- ~87 pages bloated with **60+ thin SEO "city" pages** + leftover test/duplicate pages → consolidate into one templated "Areas We Serve" pattern; kill test/junk pages.
- Equipment/capabilities (their real differentiator) under-sold; specs scattered.
- Mixed contact info (info@swwj-laser.com vs info@swwj.com) — unify.

## 4. Keep / reuse
- Logo + NTMA and ISO 9001:2015 badges (in ./images), line-card PDF and flyer.
- Real specs (machine models, capacities, tolerances, materials, file formats) — these are the credibility.
- Tagline and the "fast quote / two shifts / largest waterjet in AZ" messaging.

## 5. Proposed information architecture
- **Home** (hero + value prop + capability cards + RFQ CTA + certs + equipment highlights)
- **Capabilities:** Laser Cutting · Tube Laser Cutting · Waterjet Cutting · Press-Brake Bending · 2D Inspection · Material Sales
- **Equipment** (the machine list as a spec showcase)
- **Materials We Cut** (filterable list)
- **Industries Served**
- **Quality** (ISO 9001:2015, inspection, docs)
- **Resources** (Laser vs Waterjet guide, FAQs, articles, downloads)
- **Areas We Serve** (one template, programmatic regions — not 60 thin pages)
- **About / Contact / Request a Quote** (RFQ with file upload, persistent header CTA)

## 6. Visual direction
Modern industrial-precision: confident, clean, technical-but-approachable. Strong type scale,
generous whitespace, real machine/parts photography, spec tables, subtle motion. A precise,
"engineered" feel (thin rules, monospaced spec accents, sharp grid). Suggested palette: deep
graphite/steel + a single high-energy accent (laser-orange/amber or electric blue), white space,
high-contrast. Mobile-first. Fast. Accessible (WCAG AA).

---

## 7. PROMPT FOR CLAUDE DESIGN  (paste this into the design run / impeccable skill)

> Design and build a modern, conversion-focused marketing website for **Southwest Waterjet &
> Laser**, a family-owned, ISO 9001:2015-certified precision metal-cutting and forming shop in
> Phoenix, AZ with 20+ years of experience. Tagline: **"Understand. Deliver. Improve."**
>
> **Business:** Contract manufacturer offering **laser cutting, tube laser cutting (Trumpf
> TruLaser Tube 5000 — first in AZ), flat-sheet/plate fiber laser (Trumpf TruLaser 3040/5040/2030),
> waterjet cutting (OMAX 120 — largest waterjet in Arizona, 5-axis, 20'×10' bed, up to 8" steel,
> ±0.005"), press-brake bending (Trumpf TruBend 5130, 120"), and 2D inspection.** Cuts carbon &
> stainless steel, aluminum, copper, brass, nickel, titanium, tungsten, plus exotics (ceramic,
> glass, granite, carbon fiber, Kevlar, composites). Ships across the US, Mexico, and Canada.
> Differentiators: **fast quotes (4–24 hrs), two shifts/day, expedited service, largest waterjet
> capacity in AZ, factory-trained operators, ISO 9001:2015, NTMA member.**
>
> **Audience:** engineers, OEMs, fabricators and procurement buyers comparing job shops. They
> are technical and deadline-driven. **The single most important action is "Request a Quote"
> with CAD file upload** (accepts .pdf .step .stp .iges .igs .dxf .dwg .stl .sld .sat .ai .eps) —
> make this a persistent, high-contrast CTA in the header and repeated through the site, plus a
> click-to-call (480-306-7748).
>
> **Style:** modern industrial-precision — confident, clean, engineered. Strong typographic
> hierarchy, generous whitespace, sharp grid, thin rules, monospaced accents for specs, real
> machine/parts photography, subtle tasteful motion. Palette: graphite/steel neutrals + one
> high-energy accent (laser-orange or electric blue). Mobile-first, fast, WCAG AA accessible.
>
> **Pages/sections:** Home (hero with value prop + RFQ CTA, capability cards, equipment
> highlights, materials, certs/trust bar, industries, quote-process steps, testimonials/contact);
> Capabilities pages per service with real specs in clean spec tables; Equipment showcase;
> Materials We Cut; Industries Served; Quality (ISO 9001:2015 + inspection + downloads);
> Resources (Laser vs Waterjet guide, FAQs, articles); a single templated "Areas We Serve"
> pattern (do NOT create dozens of thin city pages); About; Contact; Request a Quote.
>
> **Use the provided assets** in ./images (logo, NTMA + ISO badges) and reflect the real specs.
> Prioritize trust, capability, capacity, and speed-to-quote. Deliver a cohesive design system
> (tokens, type scale, components) and responsive layouts.

---
*Reference content + downloaded assets are in `./source-crawl/site-content.md` and `./images/`.*
