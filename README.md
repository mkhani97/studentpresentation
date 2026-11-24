# Building a Smarter PMO

A scroll-through presentation of my Bird Construction IT PMO internship (Sept 2025 – Dec 2026), built as a single static page: `index.html`. There are no dependencies and no build step.

## Presenting

| Key | Action |
| --- | --- |
| ↓ / Space / Page Down / → | Next section (clickers work too) |
| ↑ / Shift+Space / Page Up / ← | Previous section |
| Home / End | First / last section |
| N | Show or hide speaker notes |
| F | Fullscreen |

The rail on the left is the building's elevation. The orange hoist climbs as you go, and the level markers (FDN, L1, L2, L3, RF) are clickable.

Each section's animation plays the first time it scrolls into view. To replay them all, refresh the page.

## Editing

All the text is in `index.html`. Each `<section class="slide">` is one stop in the talk, and its `data-notes` attribute holds the speaker notes.
