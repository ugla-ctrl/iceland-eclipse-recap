# Sources — Iceland Eclipse 2026 Recap Deck

Every claim in `../index.html` traces back to one of these. Check here before adding or changing a claim.

## Primary source: the official recap page

**https://imxp.org/iceland-eclipse** is IMXP's own live, published post-event recap page (a client-rendered React app; fetch with a headless browser, not curl, to see content). It is the highest-authority source for anything it states, and settles a real internal conflict: an Aug 3 2026 Slack thread (Lee + Mitch, DM `D0ADA2E9S4C`) has Lee ordering an X post deleted specifically because "3,333 people" was an unverifiable attendance claim at the time. By the time the official recap page went live post-event, IMXP itself published:

- **3,333 Guests · 2:07 Minutes of Totality · 287 Artists & Speakers · 5 Days Under the Glacier**
- "We came from more than 75 countries..."
- Full photographer credit list (matches `../assets/` sourcing below exactly)
- Gratitude copy ("to the people of Hellissandur and Snæfellsbær...to the glacier, for holding back the clouds")
- Midnight Sun 2027 listed as **"Secret Location, Iceland"**, not a named city — the location is deliberately not yet public, so this deck doesn't name it either, even though an internal working deck ([[project-midnight-sun-deck]]) does.

Use these numbers, not the partnership deck's pre-event projections, wherever they overlap.

## What's here

| Fact group | Source | Notes |
|---|---|---|
| Headline stats (3,333 guests, 2:07 totality, 287 artists & speakers, 5 days) | imxp.org/iceland-eclipse (official recap page, see above) | Supersedes both the partnership deck's 3,333-guest capacity target (which was itself flagged unverifiable pre-event, see above) and an earlier draft of this deck that used "3,000 sold out" from a working investor deck |
| Event basics (dates, location, max-eclipse time, 1954/2196) | Iceland Eclipse 2026 Partnership Deck, Canva `DAGmsAs3iyw` (64 pages), "introduction" section | Verbatim from the deck's own copy |
| Digital reach (1.5M page views, 750k unique visitors, 100k+ email, 82k+ FB, 44k+ IG, 12k+ X, 50M+ impressions) | Same partnership deck, "appendix / our collective reach" | Corroborated by Mitch's own Aug 19 2026 investor outreach email ("50k+ community from 75+ countries and scaling") |
| Audience demographics (35 avg age, 75% higher ed, 53/47 split, 40+ countries, high net worth) | Same partnership deck, "audience" section | |
| Setting / Hellissandur description (pop. 400), murals | Same partnership deck, "GATHER AT the edge of the world" section | |
| Programming pillars (Dance/Learn/Connect/Explore = "Fourth Contact") | Same partnership deck | |
| Real 2026 lineup (Above & Beyond, GusGus, Daði Freyr, Emilíana Torrini, CloZee, Zero 7, Sian Proctor, Ron Garan, Alex & Allyson Grey, etc.) | Gmail thread "Re: Iceland Eclipse 2026 - Press Selects" (Jelani Wright/infamouspr.com ↔ MaryLiz Bender/Andrew Glenn, im-xp.com), Aug 6–Sep 2 2026, day-by-day priority artist list | These are the actual confirmed 2026 performers/speakers, not the partnership deck's recycled Texas Eclipse community roster (see below) |
| Side quests (Into the Glacier, The Lava Tunnel, Icelandic Pool Party, helicopter tours, Ring Road excursions) | Partnership deck, "SIDE QUESTS" + sponsorship experience sections | |
| Press coverage (Condé Nast Traveler, Dazed, Live Science, Schön! Magazine) | Same Gmail "Press Selects" thread | Condé Nast on Into the Glacier; Dazed interviewed Sian Proctor, Richelle Ellis, Coco Reilly, Carl Hayden Smith; Live Science featured Sian Proctor; Schön! ran an ANNA photo diary |
| MaryLiz Bender quote ("absolutely magical and successful...") | Gmail "Re: Atomika" thread, MaryLiz Bender, 3 Sep 2026 | Real, attributed, from an actual IMXP team member's email to an external partner |
| IMXP / Secret Solstice background + press quotes (X, Thump, Uproxx) | Partnership deck, "producers" + "rewind: texas eclipse in focus" sections | Quotes are about Secret Solstice / Texas Eclipse specifically, kept attributed to those, not restated as being about Iceland Eclipse 2026 |
| Eclipse tradition timeline (1999–2026) | Partnership deck, "TRADITION" section | |
| Midnight Sun 2027 teaser (9–11 July 2027, "Secret Location, Iceland") | imxp.org/iceland-eclipse "The Passage Continues" section | Copy rewritten from scratch for this deck, not copied from the Midnight Sun working deck's own summary slide |
| Contacts (Mitch, Fred) | `~/midnight-sun-deck/sources/iceland-eclipse-partnership-deck-notes.md` | Uses Mitch's confirmed working address `mitch@im-xp.com` |
| Photos in `../assets/` | 13 photos pulled fresh from the IEpress gallery manifest (`thebaileyperspective.com/IEpress/api/selects`, 728 real Iceland Eclipse 2026 press photos), each md5-checked against every image already used in `~/midnight-sun-deck`, `~/imxp-deck`, `~/imxp-deck-v2`, `~/imxp-deck-v3` and confirmed as not previously used anywhere. Photographer list (The Bailey Perspective, Andrianna Kaimis, James Cook, Monica Cazes, Shane Baby Billy Fowler, Daniel, Thad, Nanaka, Caitlin Guidry, Lauren Bruno, Kayla Pittman, Allison Powers) matches the official recap page's own credit line exactly. `iceland-eclipse-logo.png` from `~/eclipse-flight/iceland/assets/`. No AI-generated imagery. | See "photo policy" below |

## Photo policy (important — read before adding any image)

**Every photo must be unique AND a visually distinct SUBJECT from what the other decks use.** Mitch's explicit complaint (2026-09-03): the recap was reusing the same shots deck.imxp (imxp-deck-v3) and Midnight Sun lead with, so the decks looked interchangeable. Two rules:
1. **Byte-unique:** pull from the IEpress manifest (`curl -A "Mozilla/5.0" https://thebaileyperspective.com/IEpress/api/selects`, then `api/thumb/<id>?sz=2048`) and `md5sum` against every file in `~/midnight-sun-deck/assets`, `~/imxp-deck*/media` or `/slides`, and this deck's own `assets/`. (This caught the eclipse-through-clouds shot = imxp-deck-v3's `eclipse-sky.jpg`, byte-identical.)
2. **Subject-distinct:** avoid the "greatest hits" the other decks all grab — the aerial crowd, the eclipse-glasses crowd, the aurora borealis, the golden-hour hug, the diamond-ring eclipse. The IEpress gallery has 728 photos; use the characterful, less-obvious ones.

**Current distinct set (all byte-verified unique, 2026-09-03):** cover = Snæfellsjökull glacier over farmstead landscape; the-moment = crescent-sun eclipse through clouds (Daniel, NOT the Bailey diamond-ring that imxp uses); numbers = sacred fire ceremony circle; reach-bg = blue-lit geodesic dome DJ stage; setting = Icelandic church-on-the-road (Hellissandur); programming-bg = Apashe performer, mic to sky; sidequests = glowing eclipse-ring "Push the Future" installation; community = antlered-crown costumed festival-goer portrait; partnership-bg = GusGus DJ in blue smoke; tradition = Temple of the Bird Tribes ceremony; whatsnext = festival grounds at golden-hour sunset (drone); thankyou = crowd jumping in front of the Iceland Eclipse banner; press = geodesic dome panel discussion.

**Under-layer backgrounds added 2026-09-04 (all byte-verified unique against this deck + midnight-sun-deck + imxp-deck/v2/v3, IEpress manifest):** trilogy-bg = darkened/cooled/blurred derivative of `setting.jpg` (Snæfellsnes church-on-the-road) as a soft-focus under-layer behind the 2D route map; moment-bg = eclipse-stage crowd watching totality (Andrianna Kaimis); setting-bg = coastal village sunset panorama (Bailey); numbers-bg = drone aerial crowd gathering (Daniel), cropped landscape; sidequests-bg = campfire gathering crowd at night (Caitlin Guidry); community-bg = eclipse-stage crowd celebrating (Allison Powers); tradition-bg = silhouettes at dusk (Thad). All applied as heavily-scrimmed `gslide underbg` under-layers so no interior slide is flat black; subjects chosen distinct from every image already used.

## Deliberately NOT included

- **The partnership deck's "notable participants" name list** (Paul Stamets, Adrian Grenier, Dr. Andrew Weil, Rick Doblin, Meow Wolf, Yuri's Night, etc.). Confirmed by directly reading the Texas Eclipse Event Recap deck (Canva `DAGE3PXQYkI`) that this is Texas Eclipse's own community roster, copy-pasted into the Iceland partnership deck's aspirational "community" section — not a confirmed 2026 Iceland roster. The real, confirmed 2026 lineup (sourced separately, see table above) is used instead.
- `recap.icelandeclipse.com` — DNS did not resolve when checked; may not be live. Use imxp.org/iceland-eclipse instead, which is live and official.

## Sourcing rules for future edits

1. **Never invent a number or claim.** Check imxp.org/iceland-eclipse first (render with headless Chrome, it's a JS app), then the partnership deck: https://www.canva.com/design/DAGmsAs3iyw
2. **No em dashes anywhere in deck copy.** House style rule. Use commas, colons, or middots (·) instead.
3. **No AI-generated imagery.** Use real event photography only, and check it's not already used elsewhere in the deck family (see photo policy above).
4. **Keep guest-facing copy positive.** Any caveat, gap, or sourcing uncertainty belongs in this file, never in the deck itself.
5. **Design language (final, 2026-09-03): match icelandeclipse.com exactly.** After iterating (dark totality -> light glass -> Texas-inspired), Mitch specified the definitive reference: the official site https://icelandeclipse.com/. Scraped its real styling and matched it: near-black ground `#09090b`, heavy uppercase display headings (site uses "Agrandir Grand Heavy"/Arial Black; deck uses **Archivo Black** from Google Fonts as the closest free stand-in), **Montserrat** (600/700) teal eyebrow labels, **Inter** body in soft light-grey `#c4c7cd` for contrast, teal `#0DFCD3` primary accent + orange `#EE7717` secondary. Stats are minimal/borderless with thin teal/orange top rules (matches the site's stat row, NOT boxed glass tiles). Press outlets are teal-outline pill **chips** echoing the site's gallery filter chips. Small corner brand lockup on interior slides. **Interactivity:** animated CSS eclipse on cover + closer (moon crosses sun to totality on a loop, teal corona bloom at totality; frozen near-total under prefers-reduced-motion); count-up animation on all stat numbers when a slide activates (handles k/M/%/+ suffixes and thousands separators, skips non-numeric like 2:07 and 53/47); hover lift/glow on pillars/chips/timeline; slow ken-burns zoom on photos per slide. Only the slide-engine JS is shared with the other decks. Do NOT revert to the Midnight Sun pastel look OR the earlier light-glass version; icelandeclipse.com is the reference. Prior rejected directions, in order: pure MSF clone (too similar), muddy dark v3 (too dark/low-contrast), light pastel glass (too light), Texas-cosmic. If re-styling, re-scrape icelandeclipse.com first.
6. Mitch's real Gmail inbox (not this session's Gmail connector, which is bound to a different account) is reachable via stored OAuth tokens: see `~/.claude/projects/-home-clawd/memory/reference_gmail_credentials.md` for the credential paths and working pattern.
