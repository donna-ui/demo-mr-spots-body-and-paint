# Mr. Spot's Body & Paint — Brief

- Business name: Mr. Spot's Body & Paint
- City: Pomona, CA
- Address: 575 S East End Ave, Pomona, CA 91766
- Phone: (909) 620-0405
- Email: mrspotauto@gmail.com
- Owner(s): Rod Gallagher (founder, since 1981) · Karess Gallagher (manager, daughter) · Tanner Gallagher (junior body specialist, son, 16)
- Status: in-progress
- Vercel URL: https://mr-spots-body-and-paint.vercel.app
- GitHub repo: https://github.com/donna-ui/demo-mr-spots-body-and-paint

## Creative direction

- **Aesthetic:** "The Restoration Masthead." A 45-year vintage-VW + classic-car shop rendered as a heritage-press masthead crossed with a paint-chip card. Old English blackletter for the brand only. Editorial restraint everywhere else. The shop has been on East End since 1981 — the site looks that old and that confident.
- **Signature moment concept:** **The Three Cars** — three editorial plates that fade into place on scroll. *1950 (a Mercury, Rod's father's). 1956 (an oval-window VW Bug, Rod's first solo). 1972 (a VW Bus, Tanner's project, still in the booth).* Cars-as-timeline frame, not people-as-timeline (the "three generations" frame is taken by Donahoo's and Pomona Locksmith).
- **Color palette:**
  - `#0f2e1f` heritage green — primary surfaces, masthead, hero, visit
  - `#0d0d0d` off-black — services section, body text
  - `#f3eee2` paint-chip cream — page background (NOT pure white)
  - `#3d7a55` mossy mid-green — hover/secondary
  - `#c9a13e` faded yellow tag — single accent (year stamps, eyebrow rules)
- **Typography:**
  - Display: **UnifrakturMaguntia** (Google Fonts blackletter) — used ONLY for the wordmark and the year numerals (1950 / 1956 / 1972) and the "Drop the car off." closing line. Precious — used 6 times across the entire page.
  - Subhead/labels: **Big Shoulders Display** (squared condensed industrial) — section titles, service names, eyebrow tags, year bands
  - Body: **Vollkorn** (humanist serif, vintage-printed-book feel) — body copy, sub-headlines, italicized maker's notes

## Voice

- Drumbeat phrase: **"Painted by Gallaghers."** — proper-noun maker's mark. Repeats in hero (huge), footer ("Painted by Gallaghers · since 1981"), and implicitly through every named family member.
- Tone keywords: heritage, plain-spoken, factual, restrained, weekday-only
- Bilingual?: no (Rod Gallagher is an Anglo-Pomona vintage-VW restorer, not a Latino bilingual shop — wrong fit)

## Pattern-break declaration *(per `feedback_break_patterns.md`)*

This site differs from my defaults on **6 axes**:
1. **Typography** — UnifrakturMaguntia blackletter display (NOT italic serif: no Newsreader, Gloock, Instrument Serif)
2. **Palette** — heritage green / off-black / paint-chip cream (NOT oxblood, NOT brass)
3. **Phone placement** — embedded in masthead crest top-center + sticky bottom rail on mobile (NOT top-right CTA)
4. **No map element** — single Pomona location, weekday only; map would be filler
5. **No chapter numbering** — no `i. ii. iii.` skeleton
6. **No grain/feTurbulence default** — flat confident color + radial gradient ambient instead

## What we've learned

- Rod started restoring at age 9, helping his father with 1950 Mercurys
- Rod's first solo project: 1956 oval-window VW Bug
- Pre-shop origin: ran mobile body+paint operation out of a Chevy pickup van
- Shop opened 1981 on East End Ave (east-side Pomona, near 71 Fwy)
- Karess "born into the industry" — direct quote from About page
- Tanner started his 1972 VW Barn Door in 7th grade; he's 16 now and still on it
- Phone discrepancy: current website lists `(909) 620-0405`; older Yelp/Facebook listings have `(714) 809-0653` — use the website number
- 12 Yelp reviews, 27 photos, 4.0★ × 5 reviews on Yahoo Local; small but genuine review base
- Existing site copy is generic ("Drive Away Happy," "former glory") — replaced entirely

## Photography note

This build ships with **zero photographs** — pure typography + color + motion. Rationale: restraint matches Rod's personality, the typographic signature is stronger than any stock photo would be, and Donna can swap in real shop photos before sending. Potential photo sources for a v2: Rod's IG `@mrspotauto`, his TikTok, the 27 Yelp photos, and on-site photography of the 1972 Bus in progress.

## Status log

- 2026-04-30: research complete, creative direction approved (cars-as-timeline pivot after pattern-overlap audit caught "three generations" was taken by Donahoo's + Pomona Locksmith), single-file Vercel build shipped, deployed to https://mr-spots-body-and-paint.vercel.app
