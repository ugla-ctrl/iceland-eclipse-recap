# Punch list: Ben's review vs. the deck as shipped

Checked against `index.html` at commit `54550d2`, live at recap.icelandeclipse.com.
Status is one of **Done**, **Done, differs**, or **Open**.

## Structure

| # | Ben asked for | Status | Note |
|---|---|---|---|
| S1 | Eclipse section = slides 1-4, unchanged | Done | Cover, The Moment, The Setting, By the Numbers |
| S2 | Festival Events section = old 6, 7, 8, 13 moved and modified | Done | Now 5 The Music, 6 The Aurora, 7 Side Quests, 8 The Ceremonies |
| S3 | Impressions and testimonials section | Done | 9 Digital Reach, 10 In the Press, 11 Testimonials |
| S4 | Who went | Done | 12 Our Community |
| S5 | What's next | Done | 13 Midnight Sun, 14 The Eclipse Trilogy |
| S6 | Thank you last | Done | 15 |

## Per-slide

| # | Ben's note | Status | What was done |
|---|---|---|---|
| B1 | p2: 2:07 is repeated | Done | The tile was removed. 2:07 now appears once, in the lead sentence. The third tile is "75 countries represented". |
| B2 | p4: drop 2:07, more event numbers and less eclipse | Done | Now 4,200 participants / 287 artists and speakers across four programmes / 4 stages / 5 days. |
| B3 | p4: fold the four categories in as "287 artists and speakers across 4 categories" | Done | Worded exactly that way, with Dance, Learn, Connect, Explore named under the 287. |
| B4 | p5 Impressions: move next to the media coverage | Done | Digital Reach now sits immediately before In the Press. |
| B5 | p6 and p7: title and subcategories duplicated, reads like advertising, consider removing both | Done | Both slides were cut, not edited. Replaced with The Music and The Aurora, written as recap. |
| B6 | Add more music and concert detail and pictures | Done | The Music carries the four stages, a night-by-night headliner list (Maribou State, Booka Shade, Emiliana Torrini / Kenny Dope, Tiga, berlioz / Above and Beyond, CloZee, ANNA, Apashe / GusGus, Nightmares On Wax, Dadi Freyr), and five new concert photographs. Every act verified against the catalog's own act tags. |
| B7 | Include the aurora during Above and Beyond | Done | Its own slide. Above and Beyond took the Eclipse Stage 23:30 Friday 14 Aug, set time taken from the catalog, and the aurora opened partway through. |
| B8 | p8 Side Quests: like it | Done | Kept, and three of its four images upgraded to real side-quest photography: Emiliana Torrini in the lava cave, sunrise yoga, the grand piano at the waterfall. |
| B9 | p9: very cool | Done | Digital Reach kept. |
| B10 | p10: CNN and testimonials are different things, move CNN to the press slide | Done | CNN clip is now on In the Press; Testimonials is standalone and full width. |
| B11 | p10: change "My favorite keepsake from Iceland" | Done | Dropped entirely on Lee's instruction (2026-09-04). Testimonials now number five, with the last row centred. |
| B12 | p10: add more testimonials | Done, differs | Five on the slide after B11 was dropped. |
| B13 | p10: show follower counts "if they have a lot of them" | Done | All five exceed 1,000 and each count is printed next to the handle. |
| B14 | p11 Our Community: very good | Done | Kept. Its collage went from two panels to three on Lee's instruction: the packed Aurora tent group shot added between Proctor/Huie and the Greys. |
| B15 | p12 Trilogy: looks great | Done | Unchanged, moved after Midnight Sun. |

## Changed since Ben's review, not from his notes

| Change | Note |
|---|---|
| In the Press rebuilt | The CNN clip and stratosphere frame are both portrait and were being centre-cropped into 16:10 boxes. Now a three-card wall where each card keeps its own aspect. |
| Imagery upgraded from the full catalog | The Setting, By the Numbers, What's Next and Thank You. |
| Photo credits corrected | Five photographers the catalog lists were missing from the credit line. |
| Footer bug fixed | An unbalanced div left the Testimonials footer outside its section, so it painted over every other slide's footer. |
| SETI broadcast still | Added as a fourth press card, then reverted at Lee's request. Slide 10 stands at three cards. |
| B16 | p13 Ceremonies: move back to the end of the festival section | Done | Now slide 8, last in that section. |

## Open, needs a decision

| # | Item | Detail |
|---|---|---|
| O1 | **4,200 participants vs 3,333 guests** | The deck says 4,200. imxp.org/iceland-eclipse, IMXP's own published recap, says 3,333 Guests. Mitch reviewed the 4,200 figure on video and did not object, so it was left. These cannot both be right and the deck is public. Needs Mitch to say which number is the real one. |
| O2 | **Digital Reach figures are not from Google Analytics** | Figures come from the partnership deck appendix. The 2026-09-04 check was run in Chrome signed in as `lencruz.work@gmail.com`, which sees only one Analytics account ("Cloon LLC", property 505390702, G-82NMBR4YTN) reporting no data. **That is the wrong Google account**, so it is not evidence that the Iceland Eclipse property is missing. Needs a re-check signed in as the account that owns it. |
| O3 | **Testimonial quality vs follower count** | ~~Open~~ **Resolved 2026-09-04.** Lee chose to relax the guests-only rule and include @naturalsymphonylive (9k): "This was so epic. What a way to open a festival." They are a credited Afterglow DJ, so the wall is now five guests plus one performer. Back to six quotes in a clean 3x2 grid. |
