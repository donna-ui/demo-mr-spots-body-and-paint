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

## Creative direction *(v3 — The Roster)*

- **Story:** Not a family shop — **a crew with extraordinary tenure.** Rod opened the doors in 1981. His master painter Jeff has been in the booth for **28 of those years.** Jose · Angel · Mario · Alias have been there 9–11 years each. Tanner (Rod's son, 16) and Karess (Rod's daughter, manager) are part of the crew, not the headline. The shop is a place people come to and don't leave.
- **Aesthetic:** Hot-rod / SoCal vintage paint shop. Heavy blackletter wordmark (Pirata One), bright kelly green, hand-painted shop-sign weight. Not editorial. Not heritage-press. The shop you'd see on East End with a sign Rod painted himself.
- **Signature moment:** **The Brush.** Hero loads black; cursor wipes the black off to reveal the bright kelly green hero with "MR SPOTS" wordmark in Pirata One blackletter. Auto-completes after 2.2s of inactivity OR after 55%+ wiped. User-driven, not scroll-linked. Mobile = touch-drag.
- **Other key moments:**
  - **The Parade** — full-bleed horizontal marquee of cars + services, paused on hover
  - **The Drag** — typographic before/after wipe of "1972 VW BUS" (paint code: Bahama Pastel) with draggable handle
  - **The Roster** — the centerpiece. 11-name crew list with tenure stamps. Jeff's "28 yrs" set 1.5x larger than the other tenures. Tagline: *"Rod opened the doors in '81. Jeff has painted in this booth for twenty-eight of those years."*
  - **Wong Kar-wai neon phone** — pulsing green text-shadow on the phone number, top-bar + visit section
- **Color palette (strict):**
  - `#4FB055` bright kelly green — primary
  - `#62c668` highlight / `#3a9442` hover-deep
  - `#0a0a0a` ink / `#161616` ink-soft
  - `#ffffff` white / `#f6f3eb` paper-cream (only used for the Roster section's symmetric tableau)
- **Typography:**
  - **Pirata One** (heavy blackletter, hot-rod weight) — used ONLY for the wordmark "MR SPOTS" in topbar, hero brush-reveal, footer. Precious. ~3 uses.
  - **Big Shoulders Display 900** — does ALL display heavy lifting: hero drumbeat, parade marquee, drag stage type, roster names + tenures, visit headline + call number
  - **Archivo** — body copy
  - **Special Elite** — typewriter mono for paint codes, eyebrows, signature lines

## Voice

- Drumbeat phrase: **"The shop nobody leaves."** — specific, repeatable, factual. Repeats in hero, roster sign-off, footer.
- Tone keywords: tenure, trust, proof, plain-spoken, weekday-only
- Bilingual?: no (Anglo-led ownership; crew is mixed but no bilingual copy needed)
- Drumbeat history: v1 used "Three generations. One shop floor." (rejected — taken by Donahoo's + Pomona Locksmith). v2 used "Painted by Gallaghers." (rejected — implies only family paints, but the master painter has been there 28 years and is not a Gallagher).

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

## The full crew (from About page)

| | | |
|---|---|---|
| Rod | Owner | since '81 |
| Jeff | Master Painter | 28 years |
| Jose | Lead Detail · Prep | 11 years |
| Angel | Lead Prep · Auto Body | 11 years |
| Mario | Lead Metal Fab · Auto Body | 10 years |
| Alias | Lead Metal Fab · Auto Body | 9 years |
| Pedro | Lead Detail | 4 years |
| Karess | Manager · Rod's daughter | family |
| Tanner | Junior Body Specialist · Rod's son · 16 | family |
| Gonzo | Metal Fab · Auto Body | crew |
| Eddy | Lead Prep · Painter | 3 months |

## Status log

- **2026-04-30 (v1):** First draft shipped — "Three generations. One shop floor." headline. Donna rejected: (a) too AI-template, (b) "three generations" frame already taken by Donahoo's + Pomona Locksmith.
- **2026-04-30 (v2):** Rebuilt from zero with The Brush signature (cursor-paint canvas wipe), bright kelly green `#4FB055`, blackletter wordmark only, marquee parade, drag-wipe before/after, Wes Anderson family tableau, neon-glow phone. Donna pushed back: blackletter font wasn't extra-bold enough, story was wrong (the family isn't the headline, the crew is).
- **2026-04-30 (v3):** Pivot — the crew is the story. Drumbeat → "The shop nobody leaves." Family tableau → The Roster (11 names + tenures, Jeff 28 yrs the screenshot). Font → Pirata One (heavy blackletter, hot-rod / SoCal weight). Live at https://mr-spots-body-and-paint.vercel.app
