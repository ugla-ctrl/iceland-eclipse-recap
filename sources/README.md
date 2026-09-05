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
5. **Design language (final, 2026-09-03): match icelandeclipse.com exactly.** After iterating (dark totality -> light glass -> Texas-inspired), Mitch specified the definitive reference: the official site https://icelandeclipse.com/. Scraped its real styling and matched it: near-black ground `#09090b`, heavy uppercase display headings (site uses "Agrandir Grand Heavy"/Arial Black; deck uses **Archivo Black** from Google Fonts as the closest free stand-in), **Montserrat** (600/700) teal eyebrow labels, **Inter** body in soft light-grey `#c4c7cd` for contrast, teal `#0DFCD3` primary accent + orange `#EE7717` secondary. Stats are minimal/borderless with thin teal/orange top rules (matches the site's stat row, NOT boxed glass tiles). Press outlets are teal-outline pill **chips** echoing the site's gallery filter chips. Small corner brand lockup on interior slides. **Interactivity:** animated CSS eclipse on cover + closer (moon crosses sun to totality on a loop, teal corona bloom at totality; frozen near-total under prefers-reduced-motion); hover lift/glow on pillars/chips/timeline; slow ken-burns zoom on photos per slide. Only the slide-engine JS is shared with the other decks. Do NOT revert to the Midnight Sun pastel look OR the earlier light-glass version; icelandeclipse.com is the reference. Prior rejected directions, in order: pure MSF clone (too similar), muddy dark v3 (too dark/low-contrast), light pastel glass (too light), Texas-cosmic. If re-styling, re-scrape icelandeclipse.com first.
6. Mitch's real Gmail inbox (not this session's Gmail connector, which is bound to a different account) is reachable via stored OAuth tokens: see `~/.claude/projects/-home-clawd/memory/reference_gmail_credentials.md` for the credential paths and working pattern.

## The Setting photo (2026-09-05, final)

Mitch asked for the ram-mural shot to be changed. A six-tile Iceland collage was built and
then dropped at Lee's request: the slide is back to **one** photo, the original
Ingjaldsholl church on the road with Snaefellsjokull behind, which is the shot Mitch said
he liked. The collage tiles and the moss-pods candidate were removed from `assets/`.

Open thread: Lee remembers a moss- or grass-covered miniature village somewhere in the
728-photo IEpress selects. "GREEN TEXTURED MODULAR PODS" (Thad, 12 Aug) was tried and is
not it. Roughly 1,050 photos of the 7,752-file organize catalog were also reviewed by eye
without finding it. Note the organize catalog carries no descriptive filenames; the IEpress
selects do, so search those names first.

## Cover background video (2026-09-05)

Mitch, in the Lee DM 2026-09-04 22:12: "Ok have you seen the drone video?" then
"It would be cool to get that in there" and "As a background". He did not say which slide.
It is now the **cover** background, which is the only slide that was already a full-bleed
background plate.

Source: `ECLIPSE_DAY2.mp4`, Slack file `F0BV0P380DB`, 302 MB, 3840x2160, 51s.
Prepared for web as `assets/cover-drone.mp4`: trimmed to 6s-45s to drop the branded title
card at the head and the Eclipse Festival logo card at the tail, since the cover carries
its own logo; scaled to 1600x900, 24fps, no audio, H.264 main, CRF 31, faststart. 8.9 MB.
Muted, looping, autoplaying, with `cover.jpg` as the poster so a blocked or failed video
falls back to the previous still. Paused under prefers-reduced-motion. The slide-change
handler that unmutes deck videos explicitly skips `.bgvid`, so it never plays sound.

## Videos in the deck (2026-09-05)

| Slide | File | Source | Behaviour |
|---|---|---|---|
| 2 The Moment | `drone-site.mp4` | `ECLIPSE_DAY2.mp4`, 302 MB 4K, trimmed 6s-45s and re-encoded to 1600x900 | Background, muted, looping. Mitch: "maybe this second page with something overlaid." |
| 10 The Ceremonies | `ceremony-live.mp4` | 17s 1080p clip Lee sent 5 Sep, re-encoded to H.264 | Background, silent (`.mutedbg`), looping, `blur(4px)` with `brightness(1.28)` under a light gradient. The Music went back to its still. |
| 7 The Aurora | `aurora-bg.mp4` | Mitch's 19s phone clip, Slack `F0BV45BJFU6`, 464x832 | **Slide background**, looping, silent (`.mutedbg`). The accent frame keeps the still photo. |

The aurora clip was briefly put in the accent frame instead; Lee reversed that. It is cut to
the 13.0s-19.4s stretch where the ribbon is strongest, cropped from the portrait source to a
16:9 window centred on the ribbon (`crop=464:261:0:520`), upscaled to 1600x900 and lifted with
`eq=brightness=0.04:saturation=1.15`. Because the source is only 464px wide, the background is soft, so it is deliberately blurred
(`blur(7px)` with a 1.06 scale to hide the blurred edges) and lifted hard
(`brightness(2.05) saturate(1.3)`) under a much lighter scrim. The blur is what lets the
background be bright enough to read as an aurora while the copy over it stays legible. The
mobile scrim is kept heavier, since the text sits over the middle of the frame there.
| 12 In the Press | `cnn-eclipse.mp4` | CNN TikTok | Plays with sound when the slide activates |
| 6 The Music | `lineup-reel.mp4` | @icelandeclipse Instagram reel, 8 Jun, pulled from the CDN as separate DASH video and audio tracks and muxed | In a 9:16 frame, replacing the three-photo grid Mitch said "doesn't do us any favors". Trimmed 1.4s-10.6s so it ends on "Totality Awaits" and drops the "Join us / icelandeclipse.com" and "Passes now on sale" cards, which are sales copy on a recap deck. |
| 11 Digital Reach | `reach-bg.mp4` | Catalog: "Daniel - CROWD AT COASTAL SUNSET", 1080x1920 | Background. Cropped to a 16:9 window on the crowd. |
| 13 Testimonials | `voices-bg.mp4` | Catalog: "Caitlin Guidry - GROUP RESTING OUTDOORS", 4K | Background, dimmed and blurred hard because six quotes sit across the whole slide. |

Slides with a video background also get a lighter treatment than the photo under-layers:
the video sits at 0.8 opacity under a gradient that stays dark on the text side and clears
to 0.3 over the footage, so the video reads as footage rather than a dark wash.

All background videos carry class `bgvid`: the slide-change handler plays them on the active
slide, pauses them elsewhere, and skips them under prefers-reduced-motion. Each has a poster
so a blocked video falls back to a still.

**Sound.** All six background videos play with their own audio. They were silent at first, which was my assumption and not anyone's instruction.
Lee pushed back ("who says it should be silent background?"), so all three were re-encoded
keeping their original audio (AAC 96k) and now play with sound, using the same
unmute-with-muted-fallback path as the CNN clip. Only one slide is active at a time and the
others are paused, so audio never overlaps. A background that should stay silent gets the
extra class `mutedbg`.

The Aurora and Ceremonies backgrounds were muted for a while at Lee's request, then unmuted
again on 2026-09-05 when she said she liked the sound. Note for next time: muting them the
first time, I also re-encoded both with `-an`, which stripped the audio out of the files, so
restoring the sound needed a re-encode from source rather than just dropping the class. Use
`mutedbg` alone to silence a background; never strip the track.

## Mobile

The per-slide corner lockup moves into the active slide's scroll flow as its last element,
right-aligned, so on a phone it sits at the bottom of that slide's own content and cannot
overlap anything at any scroll position. Desktop keeps the top-corner placement. The closer
photo is dimmed further on mobile and its logo capped, because the sun flare in that shot
was washing out the gratitude copy and the contact block.

## The Moment's stat tiles (2026-09-05)

Mitch sent a screenshot of the 1954 / 2196 tiles with "Find new stats", and in his fourth
video said of that slide "try to leave out the things that I haven't already said, just the
numbers right there". He is right: the copy directly above already says 1954 and 2196, so the
tiles repeated the prose. 75 countries also reappears on By the Numbers.

Replaced with three eclipse facts that appear nowhere else in the deck, all externally sourced:

| Tile | Label | Source |
|---|---|---|
| 27 years | Since Europe last saw totality (11 Aug 1999) | Time, BBC Sky at Night, severe-weather.eu |
| 290 km | Width of the shadow's path (about 180 miles) | nationaleclipse.com, Exploratorium |
| 2:18 | The longest totality on Earth that day | timeanddate.com |

The unit sits **inside** the big number, not in the caption. A bare "290" over the words
"kilometres wide" makes the reader assemble the fact themselves; "290 km" lands on sight.
Same for "27 years". Lee's note: numbers on their own do not mean anything to the audience.

2:18 is deliberate: it sets the deck's own 2:07 against the planetary maximum, so the number
earns its place instead of restating the lead. 1954 and 2196 stay in the prose where they were
already stated once.

## Collage treatment (2026-09-05)

Lee: no borders inside a collage, and the seams should not read as hard cuts.

- `the-moment.jpg` had a 10px white border and 10px gutters baked into the file. Recut with
  the three panels butted: 1240x1560 becomes 1210x1540.
- `community.jpg` had three panels of very different exposure meeting at hard lines (a bright
  indoor portrait, a bright grey crowd, a dark stage). Each panel is now pulled partway toward
  a common mean so they read as one piece, and each seam is feathered over a 58px band that
  dips to 50% at the line, so the joins read as soft folds rather than cuts. The panels are
  separate photographs, so a true cross-fade would ghost two scenes together; feathering is
  the treatment that actually works here.
- The `.accent` card's own 1px outline is gone, and the Community collage no longer sits in
  a card at all: it was letterboxed inside one, so dark card showed at its left and right
  edges and read as a frame. The rounded corner and shadow now live on the image itself.

## Video weight (2026-09-05)

Lee: the deck got too heavy, and the backgrounds are blurred anyway so there is no point
holding them at high resolution. Re-encoded every video from its original source, sized to
how it is actually used rather than to a single blanket setting:

| File | Was | Now | Why |
|---|---|---|---|
| `drone-site.mp4` | 1600x900, 9.0 MB | 1280x720, 4.9 MB | Slide 2's background, shown sharp, so it keeps the most resolution |
| `ceremony-live.mp4` | 1600x900, 7.6 MB | 854x480, 1.7 MB | `blur(4px)` |
| `voices-bg.mp4` | 1600x2844, 8.4 MB | 854x480, 1.8 MB | `blur(3px)`, and it was portrait: the source carries a -90 rotation flag, so most of those pixels were being cropped away unseen. Now cropped to 16:9 at source. |
| `aurora-bg.mp4` | 1600x900, 0.7 MB | 854x480, 0.2 MB | `blur(7px)` |
| `reach-bg.mp4` | 1600x900, 2.0 MB | 1280x720, 1.0 MB | Not blurred |
| `lineup-reel.mp4` | 1280 tall, 1.0 MB | 960 tall, 0.5 MB | Displayed about 360px wide |
| `cnn-eclipse.mp4` | 720x1280, 3.6 MB | 540x960, 1.6 MB | Displayed about 250px wide |

Video total 32.3 MB to 10.9 MB; `assets/` 48 MB to 26 MB. Audio kept on all seven, at 64k.
Rule of thumb: a background under a blur does not need more than 480p, and no video needs
more pixels than the box it is displayed in.

### Second pass, images and loading (2026-09-05)

Once the video came down, the **images were the heavier half**. Backgrounds were 2048px JPEGs
at high quality sitting under scrims at 0.3 to 0.5 opacity, some blurred as well.

- Background plates capped at 1500px, quality 76. Images shown sharp capped at 1600px,
  quality 82. All progressive and optimised. JPEG total 12.7 MB to 6.5 MB.
- Six orphaned files deleted: `music-ab-crowd.jpg`, `partnership-bg.jpg`, `press-seti.jpg`,
  `press.jpg`, `schedule-bg.jpg`, `trilogy-globe.png`. 1.6 MB of assets nothing referenced.
- Videos switched from `preload="auto"` to `preload="none"`, so a background is only fetched
  when its slide is reached rather than all seven downloading at once. `go()` now also warms
  the videos on the slides either side of the active one, so arriving is not a cold start.

`assets/` 48 MB to 17 MB across the two passes, with no visible change to any slide.
