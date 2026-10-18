# Ana Begali Cleaning Services — handoff at ~60%

**Live:** https://10elizabethbell.github.io/anaBegaliCleaning/ · **Repo:** https://github.com/10elizabethbell/anaBegaliCleaning · **Built:** 2026-10-18 from Muse brief (run 2026-10-18, Facebook group ad in "CONTRACTORS NJ/PA Conncted")

## What's built
- One page, `index.html`, phone first: header (wordmark + tap-to-call number top-right), hero, What we clean, Quality / organization / punctuality, Get a free quote form, close, footer.
- **World:** window-washing day. Fresh-linen mint ground, their 💚 as the brand green, soap-blue for form focus, deep green (not black) close.
- **Signature element:** the hero is a sunlit window glazed in soap film, looking out on Philly rowhouses and a hazy Center City skyline. A squeegee pulls clean strips through it on its own (two strokes, then a rest) until you touch it; then your finger or mouse is the squeegee, in any direction. The film slowly creeps back (`WIN.REGROW`). Soap bubbles drift up, get pushed by the pointer, and pop when the blade crosses them. Wave "wet-line" seams between sections move on the same loop. Tunables are in the `WIN` object at the top of the script.
- **Contact:** header number is `tel:+12672557148`. "Send us a text" opens SMS with a greeting. Service rows jump to the form with that service ticked. The form composes a text (`sms:+12672557148?&body=...`) with name, services, area, size, day, notes; name and at least one service required, with inline errors. A "Rather talk? Call" link sits under the submit button.
- Favicon / home-screen icon: "AB" lettering on the brand green (no logo exists). `og.jpg` 1200x630 for the Facebook link preview.

## Assumptions I made
- **Green** comes from the 💚 in their captions; no logo or brand colors exist.
- **"We" voice**, because the ad says "we". Ana Begali is not called the owner anywhere (brief: unconfirmed).
- **Headline "Come home to clean."** is mine. The promise line ("Focus on your day. We'll take care of the cleaning.") and the close ("Your home deserves special care.") are their own words, emoji removed.
- **The three promise lines** under Quality / Organization / Punctuality are my wording of their stated commitment ("We are committed to quality, organization, and punctuality!"). Owner should confirm they're true to how they work.
- **Services** split into seven short items from their five lines (regular / deep, Airbnb / move-in-out separated).
- **The window view** (rowhouses, skyline) is a drawn, generic Philadelphia scene, not a real location.
- Placeholder examples in the form ("Fishtown, Cherry Hill", "2 bedrooms, 1 bath") are illustrations only.

## Placeholders and gaps
- **No Facebook link anywhere.** The only profile is Ana Silvia Begali's personal one (selfies, Portuguese bio), and "see more of our work" leading there would disappoint. Add it if the owner wants it, or once there's a business page.
- **No photos of work, no before/afters, no reviews**, so there's no proof section. The ad photo (Facebook group post) needs a logged-in browser; Muse couldn't download it and neither could I.
- **No email** (none found), so the footer has none.
- Hours, years in business, prices, insurance: unknown, not mentioned.
- Whether the number takes texts is unknown. Texting is the quote path, with calling in the header and under the form.

## Questions for the owner
- Does (267) 255-7148 take texts?
- Can we have 3–6 photos of finished jobs, ideally before/after pairs? A before/after slider would replace a section's worth of copy.
- Do you have a logo or colors you already use?
- Which towns past Philadelphia do you cover (Delaware County, Montgomery County, South Jersey)?
- Hours, and whether you do weekends or same-week jobs?
- Are you insured / bonded? Any reviews from clients we can quote word for word?
- Is "Ana Begali" the right person to name, and do you want your name and face on the site?

## Ideas not built (yours to pick)
- **Runner-up world:** dust motes floating in a sunbeam across a wood floor; your finger sweeps them away and the floor shines.
- Before/after sliders inside the service rows once photos exist.
- A Facebook / Google Business profile set-up as the next favour (they have zero web presence).
- Little sparkle reward when a whole pane is cleaned; "Airbnb host" quick form with check-out time and turnover window.
- Spanish/Portuguese toggle (the poster's bio is Portuguese; Philly customers may be too).

## Not verified
- Real-device touch on iPhone/Android and inside Facebook's in-app browser (headless touch and mouse sweeps both clean the glass, including upward drags).
- The SMS handoff on real iOS and Android (body encoding checked by construction only).
- Frame rate on older phones.
- Headless screenshots drop the wipe canvas at long budgets (known Chrome artifact), so `og.jpg` shows the window already clean.
