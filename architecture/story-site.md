# SOP — one-scroll story site

## Goal
$20k-feel marketing page. Static. Brand from Firecrawl. Media from Imagine stills (video blocked by ZDR).

## Inputs
- Brand tokens in CLAUDE.md
- `public/assets/{hero-desktop,hero-mobile,room,package}.jpg`

## Logic
1. Sticky stage 320vh; scroll progress 0–1 scales the still and draws the SVG filament.
2. Three beats swap on 0 / 0.33 / 0.66.
3. Remaining panels are full-viewport still + copy. One idea each.
4. Unlock form builds a mailto to joshua@hhinvestigations.com.

## Edge cases
- Coarse pointers: hide custom cursor.
- Reduced motion: freeze Ken Burns.
- Mobile: picture element swaps 9:16 hero.
