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
- Public record says "in Southern California since 1981" (NOT specifically Pomona since '81 — that was a v3 inference). The 575 S East End Ave address is the *current* shop, not necessarily the original.
- **Open thread (2026-05-04):** Donna says Rod is originally from **Orange County** and moved over a while ago. Public sources I checked (official About page, Facebook, Yelp Pomona + Ontario, Yahoo Local, BBB, IG) don't confirm OC roots. There IS a Yelp/Facebook listing under "Ontario, CA" (`mr-spots-body-and-paint-ontario-2`) but Ontario is San Bernardino County, not OC. Awaiting Donna's source before adding OC roots to copy.
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
- **2026-05-01 (v4):** Applied new conversion-copy about-page rule. Added a **Rod / VW lede** above the Drag stage — transformation-framed headline ("Your '56 Bug looks like '56 again."), 2-col body with (a) lineage credentials = experience, not paper, traced to public sources (started age 9, first car 1956 oval-window Bug, 47 years, 1981 East End opening) and (b) wrong-fit positioning = collision *and* frame-off vintage, framed as "two different jobs, same shop, different hands." Drag eyebrow tweaked to tie Tanner's '72 Bus back to Rod's lineage. Meta description rewritten to lead with VW restoration. Section count unchanged at 5. **Note:** Public record yields no ASE, I-CAR, awards, or magazine features — credentials are framed as experience-based. If Rod has actual paper certifications, swap them in post-sign.
- **2026-05-04 (v5):** Hero pivot from kelly-green/Pirata to **Fashion Grey (`#8c8a82`) + large VW roundel watermark**. Logo image replaces Pirata wordmark in topbar + footer (Pirata One font dropped). Lime green demoted to accent only — neon phones, hero meta dots, parade separator dots, Drag "after" reveal, Roster tenures, Visit eyebrow/CTA/"Mon thru Fri" highlight. **The Brush signature removed** — didn't fit the heritage restoration frame; Drag is now the only signature animation. Mobile fixes shipped same pass: brush canvas was blocking mobile scroll (touch-action: none + black undercoat trapped users on a black hero); before/after slider was hijacking vertical scroll on touch — both resolved (slider now detects horizontal intent before locking drag).
- **2026-05-04 (v5.2):** Fact correction — Donna flagged that the shop has NOT been at the East End address since '81; Rod is originally from Orange County and moved over later. Pulled the false "same shop, same East End address since '81" line from credentials column and meta description. Replaced credentials line with verifiable arc: "Mobile out of a Chevy pickup, then a shop of his own. Forty-seven years in." Public sources don't currently confirm OC origin — see "What we've learned" open thread. Will incorporate OC + accurate move date once Donna shares her source.
