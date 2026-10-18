---
name: Ana Begali Cleaning Services
description: Window-washing day in Philadelphia. Fresh-linen mint, their green, soap-blue for focus.
colors:
  green: "#1d7a55"
  green-hi: "#16664a"
  soap: "#2c7cc6"
  deep: "#0f3f31"
  ground: "#f5f9f6"
  hero-mint: "#e6f1ea"
  ink: "#10302a"
  ink-soft: "#3b5a51"
  line: "#cfe0d6"
  field-stroke: "#7a978a"
  mist-on-deep: "#bcd8ca"
  seam-mint: "#9fd0b8"
  seam-sky: "#bfe0f0"
  frame: "#fbfcfa"
  error: "#b3261e"
  white: "#ffffff"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2.75rem, 12.5vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2rem, 8vw, 3.4rem)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.01em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.4
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    lineHeight: 1
  phone:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 800
    fontFeature: "tnum"
rounded:
  pane: "4px"
  frame: "10px"
  field: "12px"
  card: "16px"
  pill: "999px"
spacing:
  gutter-phone: "16px"
  gutter-wide: "32px"
  section-top: "40px"
  section-bottom: "48px"
  column-gap: "56px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.green}"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.green-hi}"
    textColor: "{colors.white}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.green}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-secondary-hover:
    backgroundColor: "{colors.green}"
    textColor: "{colors.white}"
  header-tel:
    textColor: "{colors.ink}"
    typography: "{typography.phone}"
    height: "44px"
    padding: "0 4px"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    height: "64px"
    padding: "10px 2px"
  service-row-arrow:
    backgroundColor: "#e3eee8"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "40px"
  service-row-arrow-hover:
    backgroundColor: "{colors.green}"
    textColor: "{colors.white}"
  chip:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "44px"
  chip-selected:
    backgroundColor: "{colors.green}"
    textColor: "{colors.white}"
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "12px 14px"
    height: "52px"
  quote-card:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.card}"
    padding: "20px 16px"
  close-band:
    backgroundColor: "{colors.deep}"
    textColor: "{colors.mist-on-deep}"
---

# Design System: Ana Begali Cleaning Services

## Overview

**Creative North Star: "The Window Comes Clean"**

The whole system is window-washing day in a Philadelphia rowhouse: soap film on a sunlit pane, a squeegee pulling a clean strip through it, bubbles drifting and popping, and the wet line the blade leaves behind. The page is fresh-linen mint and white, set in one heavy uppercase voice, with a single green taken from the business's own green-heart emoji for the things you press. Soap blue is the color of attention: it shows where focus is, and inside the form it rings the control under your finger.

It's a phone-first page for one action: call or text for a quote. Density stays low and calm. Each band of the page is one flat tint, and the bands meet at a moving wave seam rather than a hard edge. The only real depth is the window frame in the hero, which sits off the mint like a physical object. Everything else is flat, so the window is where you look.

The hero is an instrument, not an illustration. The visitor drags the squeegee across the glass, the film slowly creeps back, and the auto-squeegee resumes after a pause. Every animated piece shares one animation loop and stops under reduced motion.

**Key Characteristics:**
- Mint-and-white tonal bands that meet at animated squeegee-line seams; deep forest green for the closing band.
- One weight-900 uppercase voice for display and headings with tight negative tracking; plain sentence-case body underneath.
- Green means pressable. Soap blue means focus, and inside the form it also means hover.
- Pill-shaped controls at 44-56px, sized for thumbs.
- One lifted object (the window); everything else flat.

## Colors

A cool, low-chroma mint world with one saturated green for action and one soap blue for focus.

### Primary
- **Begali Green** (`green`): filled buttons, the outline and text of secondary buttons, the hover fill of service-row arrows, selected chips, step numerals, care-section subheads, the header phone icon and phone hover. It's also the squeegee handle in the canvas.
- **Pressed Green** (`green-hi`): hover state of filled buttons only.

### Secondary
- **Soap Blue** (`soap`): the sitewide `:focus-visible` ring (3px, 3px offset). Inside the quote form it is also the hover and focus stroke for text fields, chips and the form's buttons, plus the chip "picked" pulse. It never fills a surface.

### Neutral
- **Fresh Linen** (`ground`): page ground; services and care bands.
- **Hero Mint** (`hero-mint`): header, hero and quote band; also `theme-color`.
- **Rowhouse Ink** (`ink`): all primary text and the service-row arrow glyph at rest.
- **Damp Slate** (`ink-soft`): leads, promise line, wordmark subline, care body copy, "(optional)" hints.
- **Grout Line** (`line`): hairline dividers between service rows.
- **Field Stroke** (`field-stroke`): 2px resting border on chips and text fields (about 3:1 on white, the floor for a control boundary).
- **Forest Close** (`deep`): closing band and footer.
- **Mist on Deep** (`mist-on-deep`): secondary text on the forest close band and footer.
- **Wet Mint / Wet Sky** (`seam-mint`, `seam-sky`): the two 2px strokes riding every wave seam.
- **Window Frame** (`frame`): the window frame and mullions.
- **Error Red** (`error`): inline form validation messages.

### Named Rules
**The Green Is a Button Rule.** Begali Green marks things you can press, plus the care subheads and step numerals that belong to the same voice. It doesn't tint section backgrounds or decorate text that does nothing.

**The Accent on Hover Rule.** Accents show up on interaction, not at rest. Service-row arrows rest as neutral mint discs (`#e3eee8`) with ink glyphs and fill green only on hover, focus or press. Text fields and chips rest in Field Stroke and turn soap blue on hover.

**The Soap Means Focus Rule.** Soap blue is spent only on focus, and on form-control hover. Don't use it for buttons, links or fills, so a keyboard user always knows what it means.

## Typography

**Display Font:** system UI sans stack (-apple-system, Segoe UI, Roboto, Helvetica, Arial)
**Body Font:** the same stack

**Character:** One family carries everything. Weight 900, uppercase and tight tracking make the headings; regular weight makes the body. Headings read like stenciled lettering on a work van, and body copy reads like a friendly note. (The system stack is Ellie's house choice for pitch sites: fast on cellular, no font download.)

### Hierarchy
- **Display** (900, `clamp(2.75rem, 12.5vw, 6rem)` on phones and `clamp(4rem, 6vw, 5.25rem)` from 1000px, line-height 0.92, -0.035em, uppercase): the hero headline only. A few words, with a deliberate line break.
- **Headline** (900, `clamp(2rem, 8vw, 3.4rem)`, 1.02, -0.02em, uppercase, balanced wrap): one per section, capped at 12-13ch where it's a statement.
- **Title** (800, 1.375rem on phones and 1.4rem from 1000px, -0.01em): service-row labels. Care subheads use 900 uppercase at 1.25rem in green.
- **Lead** (400, 1.25rem, 1.4, Damp Slate): the hero promise (30ch) and section leads (36ch).
- **Body** (400, 17px, 1.55): copy, max 38ch in the care columns.
- **Label** (800, 1.0625rem, line-height 1): buttons, form legends and labels. Chips are 700 at 1rem.
- **Phone** (800 with tabular numerals): the header number; the close's big number is 900 at `clamp(1.7rem, 8vw, 2.6rem)`.

### Named Rules
**The Heavy Caps Rule.** Display and headline are always weight 900, uppercase, with negative tracking. Body text is never uppercase. The one small uppercase, tracked line is the wordmark's "Cleaning Services" subline, which is part of the logo lettering, not a reusable label style.

**The Tabular Phone Rule.** Every rendering of the phone number uses tabular numerals and `white-space: nowrap` so it never wraps mid-number.

## Layout

Single column on phones, centered in a 1180px container with 16px gutters (32px from 700px; both respect `env(safe-area-inset-*)`). Sections run 40px top and 48px bottom by default, tightened where a seam already supplies the break. From 1000px the hero splits into text and window (1.1fr / 1fr, 56px gap), the service rows flow into two CSS columns (56px gap), and from 1024px the quote band becomes intro and form (0.8fr / 1.2fr) with the intro sticky at 24px. The care vows go to three columns at 800px. A landscape-phone rule (max-height 500px) puts the hero side by side and scales the headline by `vh`. Bands run full-bleed edge to edge; only content sits in the container.

**The Bands and Seams Rule.** Each section is one flat tint: Hero Mint, Fresh Linen, Hero Mint, then Forest Close. Where the tint changes, an animated wave seam (56px tall, 80px from 1000px) carries the transition. Never use a straight hard edge between two different tints.

## Elevation & Depth

Flat with one exception. Section bands are flat tones. Depth goes to the hero window, which sits off the mint on a long, soft, ink-tinted ambient shadow, has its own sill shadow, and has shaded mullions, so it reads as a real frame. The quote form card gets one softer lift so it separates from the mint band. Shadows are always tinted with Rowhouse Ink (`rgba(16,48,42,…)`), never neutral black, and always diffuse; no hard offsets.

### Shadow Vocabulary
- **Window lift** (`box-shadow: 0 18px 40px -18px rgba(16,48,42,.45), 0 4px 10px -4px rgba(16,48,42,.2)`): the hero window frame only.
- **Sill drop** (`box-shadow: 0 8px 16px -8px rgba(16,48,42,.4)`): the sill under the window.
- **Card lift** (`box-shadow: 0 16px 36px -22px rgba(16,48,42,.45)`): the quote form card.
- **Field glow** (`box-shadow: 0 0 0 3px rgba(44,124,198,.2)`): focused text field.

### Named Rules
**The One Lifted Object Rule.** The window is the only thing on the page that looks physically raised. Anything else that wants a shadow gets at most the card lift.

## Shapes

Round where you touch, square-ish where it's glass. Buttons and chips are full pills (`pill`), and service arrows and step numerals are circles. Text fields and the copy-fallback panel use 12px corners (`field`) and the form card 16px (`card`). The window is 10px (`frame`) around a 4px pane (`pane`), crossed by flat 10px mullions (14px from 1000px). Borders are 2px on interactive strokes and 1px hairlines between rows; nothing else carries a border.

## Components

### Buttons
Thumb-sized and confident.
- **Shape:** full pill, 56px tall, 24px side padding, 2px green border on both variants.
- **Primary (filled):** Begali Green fill with white label. On hover (hover-capable devices only) it goes to Pressed Green.
- **Secondary (outlined):** transparent with a green label and border. On hover it fills green with white text. The secondary action under the hero headline is always outlined, never a second filled button.
- **Press:** `scale(.98)` on `:active`; colour transitions 0.2s.
- **Inside the form:** full width, plus a soap-blue 3px outline on hover and focus.
- **Icons:** inline stroke SVG at 20px, `currentColor`, 2.2 stroke, round caps.

### Header phone link
The only phone number on the first screen, top right. It's the number itself as a `tel:` link, not a "Call" button: weight 800 with tabular numerals, a 44px tap target, and an 18px green handset icon. On hover the text turns green. The wordmark on the left is "Ana Begali" in 900 uppercase over the small tracked "Cleaning Services" subline.

### Service rows (signature list)
Big tappable lines that open the quote with that service preselected.
- **Rest:** title-weight label on Fresh Linen, separated by 1px Grout Line hairlines, at least 64px tall (72px from 1000px). Each row ends in a 40px neutral mint disc holding an ink arrow.
- **Hover / focus / press:** only the arrow disc changes. It fills Begali Green and the arrow turns white. The row itself never gets an outline, ring, border or background tint. The keyboard focus ring (3px green, 3px offset) goes around the arrow disc, not the row.
- **Behavior:** clicking a row ticks the matching chip in the form and plays the chip's soap pulse.

### Care vows
Three short columns: a green 900 uppercase subhead (Quality / Organization / Punctuality) over Damp Slate body copy at 38ch. They are plain text with no cards, icons or containers.

### Quote steps
A numbered list with 28px green circular numerals in white 900, set beside 700-weight lines. It's static and not interactive.

### Chips
Multi-select service choices inside the form.
- **Style:** white pill, 44px tall, 16px padding, 2px Field Stroke border, 700 label at 1rem.
- **Selected:** green fill, green border, white text.
- **Hover / focus:** the border turns soap blue. Keyboard focus adds a 3px soap outline at 2px offset.
- **Picked pulse:** when a service row preselects a chip, a soap-blue ring expands and fades over 0.9s.
- Chips are only for real choices in the form. Never use them for service areas, towns or non-interactive labels.

### Inputs / Fields
- **Style:** white fill, 2px Field Stroke border, 12px corners, at least 52px tall (textarea 96px, resizes vertically), 500 weight at 16px so iOS doesn't zoom.
- **Hover / focus:** the border turns soap blue. Focus adds the 3px soap field glow; the native outline is suppressed.
- **Labels:** 800-weight label above each field. Optional fields carry a 500-weight Damp Slate "(optional)".
- **Error:** a 700-weight Error Red line under the field, announced with `role="alert"`, with focus moved to the first failing control.

### Quote card
A white card with 16px corners and the card lift, padded 20px/16px on phones and 32px from 1024px. Submitting it opens a pre-written text message. A quiet Damp Slate line under the button says so. A pale mint fallback panel (12px corners) shows the message to copy if Messages doesn't open.

### Hero window (signature component)
A canvas window you can squeegee clean. A painted view (sky, low sun, hazy Center City towers, a brick rowhouse roofline with cornices and chimneys, soft corner leaves) sits under a soap-film layer with swirls, drips and suds. A 2D mask cuts the film wherever the blade passes. Bubbles drift up, get pushed by the pointer and pop into a ring of droplets when the blade crosses them. The steel squeegee has a green handle. When idle, an auto-squeegee runs S-strokes that step down the glass. Touch, mouse drag and desktop hover all wipe. The canvas is re-read every frame so vertical drags work. A dark translucent hint pill ("Drag to clean the glass" / "Move across the glass") fades after the first touch. Tune it through the `WIN` object only:
- `REGROW` 0.0022: how fast the film creeps back (alpha per frame).
- `BLADE` 0.30 of the glass width, capped at `BLADE_MAX` 150px.
- `GHOST_SPEED` 3.2px/frame, scaled 0.7-1.4x by width; `GHOST_ROWS` 2 strokes per pass; `GHOST_REST` 150 frames between passes.
- `IDLE_RESUME` 5000ms after the last touch before the auto-squeegee returns.
- `BUBBLES_PHONE` 12 / `BUBBLES_DESK` 22; `DPR_MAX` 1.5.
Under reduced motion it pre-wipes one clean stripe and redraws only on input.

### Wave seams
The wet line a squeegee leaves. These are full-width SVGs filled with the next band's tint (`--to`), with a Wet Sky stroke above a Wet Mint stroke on the edge. The edge is a sum of slow and fast sines, so it is organic and never ruler-straight. They are animated on the shared loop, paused offscreen and static under reduced motion.

### Close and footer
The Forest Close band carries the final headline, the service area in Mist on Deep, and the big phone number (900 weight, mint-green icon, lighter mint on hover). The footer continues the same deep tone behind a faint white hairline: business name in white, area, a white underlined phone link and the copyright line.

## Do's and Don'ts

### Do:
- **Do** keep the phone number as a `tel:` link in the header's top-right, appearing only once on the first screen. The close and footer may repeat it.
- **Do** keep at most two buttons under the hero headline, filled first and outlined second, and never a Call button there.
- **Do** give every form control (fields, chips, form buttons) a visible soap-blue stroke or outline on both hover and focus.
- **Do** change only the arrow disc on service-row hover and focus, and put the focus ring on the disc.
- **Do** join tint changes with an animated wave seam, and run every animation on the one shared loop that stops under `prefers-reduced-motion`.
- **Do** tint shadows with Rowhouse Ink and keep them diffuse, and keep lift for the window and the form card.
- **Do** keep tap targets at least 44px (56px for primary actions) and inputs at 16px or larger.
- **Do** keep organic, hand-made motion in the window and seams: a wrist curve in the squeegee stroke, sine-sum edges.

### Don't:
- **Don't** outline, ring, border or tint a service row on hover or focus.
- **Don't** use soap blue as a fill, a button color or a link color; it means focus.
- **Don't** put towns, service areas or other non-interactive labels in pills or chips.
- **Don't** add a sticky bottom contact bar or a second control that does the same thing as one already on screen.
- **Don't** add email buttons or links; this business has no email, and if one is ever supplied it lives in the footer only.
- **Don't** run seam strokes, bubbles or scene lines through text; text sits on flat band tints.
- **Don't** introduce a second lifted object that competes with the hero window.
- **Don't** swap the system UI stack for a webfont without Ellie asking; it's her house style for these sites (fast on a phone, nothing to download). Keep the 900 uppercase, tight-tracked ramp.
- **Don't** add section kickers or eyebrow labels above headlines; the wordmark subline is not a precedent for them.
