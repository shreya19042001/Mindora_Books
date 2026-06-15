# Mindora Books — Project Files

## Missing images (not uploaded, paths already referenced in code)
These files are referenced in index.html / app.js but were not part of the
uploads, so the page will show broken images until you add them to /images:

- only_logo.png        (navbar + footer icon, transparent PNG)
- logo-name.png         (navbar wordmark, transparent PNG)
- full_logo.png         (logo interstitial + footer, transparent PNG)
- b1-cover.png, b1-p2.png, b1-p3.png, b1-p4.png, b1-p5.png, b1-p6.png   (Indian Gods book)
- b2-cover.png, b2-p2.png, b2-p3.png, b2-p4.png, b2-p5.png, b2-p6.png   (Zooland book)
- b3-cover.png, b3-p2.png, b3-p3.png, b3-p4.png, b3-p5.png, b3-p6.png   (Sea Animals book)

Book covers should ideally be 8.5 x 11 in (portrait) so they display
uncropped in the carousel (object-fit: contain is used).

## New images added this round
- hero-bg.png        — colourful illustrated hero backdrop
- about-bg.png        — About section full background
- gallery-1.jpeg      — Coming Soon: Volcano Valley
- gallery-2.png       — Reviews section backdrop
- gallery-3-god.png   — Benefits section backdrop
- gallery-4-sea.png   — Coming Soon: Coral Castle Kingdom
- gallery-5.png       — For Whom section backdrop
- gallery-6.png       — Carousel backdrop (Zooland book)
- gallery-7.png       — Carousel backdrop (Indian Gods book)
- gallery-8.png       — Logo interstitial backdrop
- gallery-9.png       — Carousel backdrop (Sea Animals book)
- gallery-10.png      — Quality section backdrop
- gallery-11.png      — Coming Soon: Dino & Dragon World
- gallery-12.png      — Footer accent

## Summary of changes made
- Colourful dark theme: replaced cosmic/nebula palette with coral/teal/violet/gold orbs
- New full-screen logo interstitial section after hero (no navbar visible)
- Fixed intro animation "A" clipping (MIND/AURA/ORA)
- Reduced navbar vertical padding (smaller gap)
- Buy Now is now a dropdown (Amazon / Flipkart / Meesho / WhatsApp)
- About content placed directly over its background image
- Navbar "Contact" link fades out near the Contact section / footer
- ISBNs shown without dashes
- Book cover aspect ratio set to 8.5 x 11 (object-fit: contain, no crop)
- Page count copy updated to "56 Pages · 25+ Coloring Pages"
- New Reviews section added before About
- New "Coming Soon" teaser strip before Quality section
