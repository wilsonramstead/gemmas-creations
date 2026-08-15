# Gemma's Creations — Demo Website

Demo site for **Gemma's Creations**, St. Petersburg, FL — built by Wilson Innovations
(wilsoninnovations.net) as a pitch demo.

- **Live:** https://wilsoninnovations.net/gemmas-creations/
- **Phone:** (727) 254-1813 (tel: + sms: CTAs)
- **Hours:** none published on Google Business Profile — site uses "By appointment — call or
  text" framing throughout; NO hours section, NO hours in JSON-LD (intentional).
- **Rating shown:** 5.0 / 16 Google reviews (verified from listing)
- **Owner:** Gemma (woman-owned, hands-on) — referenced factually only, no owner-personality section

## Design

- Tier 2 (Showpiece / Night Shift) — dark editorial for a refined custom-fabric craft brand
- Fonts: **Bellefair** (display serif) + **Karma** (body serif) — per manifest
- Palette: warm charcoal `#211b1e` / warm ivory `#f3ebe6` / soft taupe `#bfa9a2` /
  dusty-rose `#c98a8a` accent — "Charcoal & Dusty Rose" (feminine craft direction, deliberately
  distinct from sibling Garth & Ally "walnut & old gold" and the auto-upholstery fleet:
  revival oxblood, bjs saddle-tan, peggs burnt-orange, gabriels cyan-teal)
- Living dusty-rose aurora background + film grain, one-shot blur/transform scroll reveals, all
  motion gated behind `prefers-reduced-motion`
- Mobile header standard: call CTA flush right, icon-only ≤600px; brand wraps, never clipped
- No fixed bottom mobile call bar; `noindex` + DEMO comment; "Website by Wilson Innovations" footer
- Single self-contained `index.html` (inline CSS/JS) + `assets/` images

## Facts source

All copy drawn from the business's Google listing and public reviews only. FURNITURE upholstery /
reupholstery + custom cushions + marine (NOT an auto shop): sofas & sleeper sofas, occasional
chairs, dining chairs, barstools, built-in banquettes, custom cushions, boat/marine seating &
covers, repairs/patching, fabric selection. GBP legal name "Gemma's Creations, LLC" cleaned to
"Gemma's Creations" per manifest. Owner **Gemma** named in reviews (hands-on, involved every step) —
referenced factually, NOT built into an owner-personality section.

Real review anecdotes used (verbatim, light normalization; first name + last initial):
six barstools reupholstered, excellent + reasonably priced (Kirsten T.); hurricane-lost boat
cushions recreated "even better than our original ones," hands-on (Anthony C. — divider pull-quote);
sleeper sofa + occasional chair, THE perfect matched sofa fabric, facilitated pickup & delivery
(Deborah B.); fabric-couch hole patched, sectional saved, reasonable + highly communicative
(Kristie K. — woven into copy); dining chairs recovered "look amazing," great communication +
turnaround (Sara O.).

**Facts deliberately left out:** no business hours (none published — "by appointment" instead);
no street address displayed or in JSON-LD (home-based/appointment shop — city + region + postal only,
tactful); no invented founding year, license, email, or pricing.

Address (Pinellas): 11248 52nd Ave N, St. Petersburg, FL 33708 (Seminole area) — displayed only as
"St. Petersburg & Seminole, FL" + Tampa Bay area.

## Photos

**All 10 images are the business's OWN Google Business Profile photos** (attribution
"Gemma's Creations, LLC"), fetched via the Places API and re-encoded with PIL ≤350KB. **No stock /
Unsplash images were used** — so no cross-site dedup or stock phash was required. Every image was
visually verified against its `alt`. No painted phone numbers appear in any photo (GBP-only phone
shipped). The owner-at-work photo (gbp_00) was cropped to a workshop close-up (industrial machine +
quilted panel), removing the subject's upper body — used tastefully for the "made by hand" strip.

| Slot | Source (GBP) | Subject |
| --- | --- | --- |
| Hero + divider bg | gbp_07 | Custom built-in kitchen banquette, printed fabric backrests, sage kitchen |
| Reupholstery feature | gbp_05 | Antique carved-walnut dining chairs re-covered in cream fabric |
| Cushions feature + CTA bg | gbp_04 | Custom L-shaped corner banquette, striped cushions |
| Craft strip ("made by hand") | gbp_00 (cropped) | Industrial machine stitching a diamond-quilted panel |
| Gallery — barstools | gbp_08 | Pair of red velvet barstools |
| Gallery — cushions | gbp_09 | Custom oatmeal linen seat cushions |
| Gallery — boat seats | gbp_02 | Grey/white diamond-stitched marine helm & boat cushions |
| Gallery — leaning post | gbp_03 | Tan diamond-stitched leaning-post boat seat |
| Gallery — motorcycle | gbp_01 | Custom crocodile-embossed motorcycle seat |
| Gallery — marine canvas | gbp_06 | Fitted navy T-top / console canvas cover |

## Verification

puppeteer-core + Edge at true 390 / 1366 / 1440 widths: **zero horizontal overflow** everywhere;
1440×900 and 1366×768 fold shots confirm the full hero stack (eyebrow → headline → sub → CTA pair →
notes → stat band) with no scroll. Every section and gallery image reviewed against its alt.

`noindex` is set while this is a demo — remove the meta tag at go-live.
