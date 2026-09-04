# Ben's review of the recap deck (2026-09-04)

Overall: "the deck looks great. Good story telling, with a good hook talking about
the eclipse first, setting the scene."

## Requested running order (implemented)

| # | Slide | Section |
|---|---|---|
| 1-4 | Cover, The Moment, The Setting, By the Numbers | **Eclipse** (unchanged) |
| 5-8 | The Music, The Aurora, Side Quests, The Ceremonies | **Festival Events** |
| 9-11 | Digital Reach, In the Press, Testimonials | **Impressions & testimonials** |
| 12 | Our Community | **Who went** |
| 13-14 | What's Next, The Eclipse Trilogy | **What's next** |
| 15 | Thank You | **Thank you** |

## Per-slide feedback and what was done

- **p2 The Moment** - "2:07 repeated." Removed the duplicate 2:07 tile; it now appears once, in the lead sentence. Replaced with "75 countries represented."
- **p4 By the Numbers** - "should be more about the event and less about the eclipse." Removed 2:07. Now: 4,200 participants / 287 artists & speakers across four programmes (Dance, Learn, Connect, Explore) / 4 stages / 5 days. The four categories moved here from the old Programming slide, exactly as Ben suggested.
- **p5 Digital Reach** - "place it next to/before the media coverage." Moved to sit directly before In the Press.
- **p6 Programming + p7 Schedule** - "duplicated title/subcategories... feels like advertising... might remove both." Both **replaced**:
  - **The Music** - a recap of what actually played (four stages, 287 artists, the four headline nights) with real concert photography.
  - **The Aurora** - the northern lights that opened over Snaefellsnes partway through Above & Beyond's 23:30 Friday set, per Ben's "INCLUDE THE AURORA DURING ABOVE AND BEYOND."
- **p8 Side Quests** - liked, unchanged.
- **p9 In the Press** - liked. The **CNN clip moved here** from the testimonials slide, since "CNN interview and testimonials are different things."
- **p10 Testimonials** - now standalone and full width. Replaced "My favorite keepsake from Iceland" with a fuller quote. Six testimonials.
- **p11 Our Community / p12 Trilogy** - liked, unchanged; Trilogy moved into the "What's next" section after Midnight Sun.
- **p13 Ceremonies** - "move it back to the end of the festival section." Done, now slide 8.

## Open item

**Follower counts on testimonial tags.** Ben suggested showing follower numbers "if they
have a lot of them." Checked every author: @salenasalinas 4.6k, @tinabrummer_balance 1.9k,
@alli_empowers 1.4k (removed, crew), @iwona.fluda 671, @exologik 662, @joshuabear.music 581.
None are large enough that a follower count strengthens the quote, so counts were **not**
added. Worth revisiting only if a high-follower guest testimonial turns up.

## New photography pulled for this round

Sourced from the full Bailey Perspective catalog (7,752 files, richer than the 728-photo
IEpress selects), all byte-checked unique:
- `music-ab-duo.jpg` - Above & Beyond performing (Jake Rosenberg)
- `music-ab-crowd.jpg` - crowd at the barrier during their set (Jake Rosenberg)
- `music-lasers.jpg` - ANNA's laser show, Aurora stage (Jake Rosenberg)
- `music-stage-night.jpg` - Eclipse Stage at night (The Bailey Perspective)
- `aurora-real.jpg` - the actual aurora borealis streak (Jake Rosenberg)

## Testimonial replacement by follower count (2026-09-04)

Lee's rule: replace any testimonial from an account with **under 1,000 followers**.
Every author checked on IG and cross-checked against the event credits.

**Removed (under 1k):** @iwona.fluda 671 · @exologik 662 · @joshuabear.music 581 · @heimirbv 444

**Now live (all >1k, all verified guests with no event credit):**
| Handle | Followers | Quote |
|---|---|---|
| @ascensionacres | 12.1k | "Amazing work." |
| @cosmobiologist (Graham Lau, astrobiologist) | 6.1k | "A fantastic group of future makers." |
| @salenasalinas | 4.6k | "My favorite keepsake from Iceland." |
| @harley_xcx | 4.1k | "Such a cool experience." |
| @tinabrummer_balance | 1.9k | "Many thanks again for making this extraordinary experience possible." |
| @hippieonahiway | 1.2k | "I love that you captured the beautiful moment we were all having." |

**Excluded despite high follower counts (crew/talent, not guests):**
- ~~`@naturalsymphonylive` (9.0k)~~ - **Included on Lee's instruction, 2026-09-04.** "This was so epic. What a way to open a festival." They are a credited Afterglow DJ, so this is talent rather than a guest, and it is the one place the guests-and-customers-only rule is knowingly broken. Lee was told and chose to include it.
- `@liam.bongo`, `@jamescook88` (96 gallery credits), `@kaylaeditsthings` (32) - all crew.

**Honest tradeoff to flag:** the >1k rule removes the four best-written quotes and leaves
shorter ones. The most articulate praise consistently comes from small accounts (attendees)
or from crew. Highest-follower guests tend to leave brief comments. Follower counts are now
shown next to each handle, per Ben.

## Catalog image upgrades, round 2 (2026-09-04)

Mined the full 7,752-file catalog (not just the 728-photo IEpress selects) and found
**Jake Rosenberg**, an editorial photographer whose 145-frame MISC set was not represented
anywhere in the deck. Six images swapped in from it (all md5-checked unique against this
deck, midnight-sun-deck and imxp-deck/v2/v3):

| Slide | Was | Now |
|---|---|---|
| 03 The Setting (accent) | Hellissandur church on the road | The ram mural on the town wall, guests walking past. Directly illustrates the "Murals of Hellissandur" paragraph. |
| 03 The Setting (under-layer) | coastal village sunset | Aerial of the town meeting the festival domes, ocean behind |
| 04 By the Numbers (accent) | drone crowd aerial | Families on the hillside watching, child in a carrier. Reads as "who came", not just "how many" |
| 13 What's Next (accent) | golden-hour grounds | Midnight sun sitting on the sea over the camp. Literal for Midnight Sun 2027 |
| 13 What's Next (under-layer) | same | Sunrise aerial of the tent village |
| 15 Thank You | crowd jumping at the banner | Sun setting through the gate structure, silhouettes watching |

Jake Rosenberg added to the photography credit line, along with Whitney Petters,
Freyr Guðjónsson, Patrick O'Leary Jr and Andrew Glenn, who are all credited in the
catalog but were missing from the deck's credits.

### Bug found and fixed while verifying

The Testimonials slide had one extra `</div>`, which pushed its footer outside the
`<section>`. That footer was therefore never hidden, and painted on top of every other
slide's footer on every slide. It was visible as doubled, overlapping footer text.
Fixed; footer text now renders once per slide.

## Lee's follow-ups, 2026-09-04 (later)

- **Dropped @salenasalinas "My favorite keepsake from Iceland"** per Ben's B11, rather
  than rewriting it. Testimonial wall is now five: @ascensionacres 12.1k,
  @cosmobiologist 6.1k, @harley_xcx 4.1k, @tinabrummer_balance 1.9k, @hippieonahiway 1.2k.
  The grid became `repeat(6,1fr)` with each quote spanning two columns and the fourth
  offset by one, so the trailing row of two sits centred instead of hanging left.
- **Our Community collage is now three layers.** Lee supplied the packed-Aurora-tent group
  shot (Dr. Sian Proctor doing the Vulcan salute with astronauts at the barrier, several
  hundred guests behind). It sits between the existing two panels: Sian Proctor with
  astronaut Huie on top, Alex and Allyson Grey on stage below. Rebuilt as 1240x1800 with
  no divider line. The accent slot for this slide switched from `object-fit:cover` to a
  `contain` layout (`.accent.commcollage`) so a taller collage is shown whole rather than
  centre-cropped.
- **Google Analytics attempt failed.** See O2 in `ben-punch-list.md`. The signed-in account
  has no Iceland Eclipse property.
- **Blocked Instagram message request dropped** from the punch list at Lee's instruction.
