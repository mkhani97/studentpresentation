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


## Hosting


**Note:** a GitHub Pages site is public even when the repo is private. Anyone with the link can open it. If the content shouldn't be public, present from the local file or put the site behind Cloudflare Access.


**Present locally (no hosting):** double-click `index.html` and it opens in your browser. Everything works offline except the web fonts.


**GitHub Pages:** your account needs GitHub Pro (or a paid org plan) to use Pages with a private repo.
1. Make sure `index.html` is at the root of the `main` branch.
2. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, then choose branch **main** and folder **/ (root)** and save.
3. Within a minute or two the site is live at `https://<username>.github.io/<repo>/`.


## Editing


All the text is in `index.html`. Each `<section class="slide">` is one stop in the talk, and its `data-notes` attribute holds the speaker notes.


To set up the LinkedIn QR code on the last section, search for `YOUR-LINKEDIN` and replace that URL with your profile URL. The QR code is generated from it automatically.


