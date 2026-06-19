# Chairside Barber Sites — brand source of truth

The single reference for colors, type, voice, and assets. Everything
(site, logo, favicon, IG, demos) pulls from here.

## Name
- **Brand:** Chairside
- **Descriptor:** Barber Sites
- **Lockup:** "Chairside · Barber Sites" / wordmark "CHAIR**SIDE**" (SIDE in amber)
- **Domain:** chairsidebarbersites.com (GoDaddy; GoDaddy-bundled M365 email)
- **Mailbox:** hello@chairsidebarbersites.com (provision in GoDaddy M365)
- **IG:** @chairsidebarbersites (confirmed 2026-06-18)

## Palette (black & sand-gold — per Gemini's logo color guidance, 2026-06-18)
| Role | Hex |
|---|---|
| Near-black (primary dark) | `#15140f` |
| Gold accent — **Sand Gold** (flat; also the emblem fill) | `#c5a059` |
| Bright gold (hover/highlight) | `#d9ba7e` |
| Off-white (main text, per Gemini) | `#f5f5f0` |
| Muted text | `#9a9078` |
| Hairline rule | `#332e23` |
- One flat gold hex on the emblem + accent text + buttons (no gradient).
  Previous bright amber `#d9a441` / cream `#f3ece0` retired 2026-06-18.

## Type
- **Wordmark:** Bebas Neue — `CHAIR` (cream) + `SIDE` (amber), kerning-fixed (-0.22em)
- **Section labels / kickers / headings:** Oswald (condensed)
- **Body:** Inter
- (Cormorant Garamond serif wordmark was trialed 2026-06-18 then reverted to Bebas
  to match the site. Tagline *a cut above a template* available if wanted.)

## Logo — FINAL (set 2026-06-18, emblem direction)
- **Mark:** the **monoline barber-chair emblem** Ashley generated (Gemini) —
  a single-line chair inside concentric rings + a segmented outer ring. Source
  board `chairside-private/chairside-logos/Gemini_Generated_Image_zgz5iozgz5iozgz5.png`
  (no "EST 2026"). Extracted by keying out the cream, recolored amber-on-`#15140f`.
- **Wordmark:** Bebas Neue `CHAIR`(cream) + `SIDE`(amber) — matches the site.
- **Lockup (OG/share):** emblem + Bebas CHAIR/SIDE + ruled `BARBER SITES` (Inter).
- **Production assets** (`scripts/extract-emblem.js` → `build-emblem-assets.js`):
  - Header mark (transparent): `chairside-site/assets/emblem-mark.png`
  - Favicons: `favicon.ico` (16+32), `favicon-16/32.png`, `apple-touch-icon.png`
  - Social: `og.png` (emblem + serif lockup, 1200×630)
  - Brand: `chairside-logos/badges/lockup-emblem-dark.png` + `-cream.png`, `web/ig-profile-320.png`
- **Caveat:** the emblem is from a ~450px raster board → sharp for header / IG /
  social / OG, soft if enlarged huge, muddy at 16px favicon. An SVG/large
  transparent re-export of the emblem would make it crisp at every size.
- Previous direction (detailed vintage chair, `IMG_8165.png`, Bebas wordmark) retired.

## Voice / positioning
- **Thesis:** On IG every barber's fades look the same; your website is where
  a stranger decides you're *theirs*. Identity, not utility.
- **Signature offer:** the personality session — "I don't send you a form. We
  talk for an hour first, then I build a site that sounds like you."
- **Two paths:** A = we host + tend it (monthly). B = $X lesson, you run it via
  Claude, no monthly. (Pricing off public surfaces — sent on request.)
- **AI angle (honest):** AI can't read your Instagram; a real structured site
  is the only thing it can see/recommend. Secondary beat, never the lead.
- Audience guardrail: Chairside→barber language ("running your shop out of your
  DMs") is for outreach/marketing; the barber's own SITE speaks to *their*
  customers ("no texting, just book").

## Asset locations (currently in localedge-private, migrating here)
- 6 barber demos: chairside-site/demo/<slug>/
- Snapshots / reels / anatomy: (private repo) snapshots/
- Scripts: snapshot-preview.js, reel-preview.js, anatomy-post.js, gen-prospect-og.js
- Content calendar: social/week-1-calendar.md
- Strategy: notes/barber-strategy.md
