# Atulyash-fresh folder map

A clean starting kit for redesigning the Atulyash homepage with no old design in it.

- `START-PROMPT.md`: the prompt to paste into a new session. Start here.
- `BRAND.md`: company, product facts, pack wording, audience, voice, Veer's character, fixed artwork, claim rules.
- `COPY.md`: every homepage line, by section (hero, manifesto, process, six questions, films, price and calculator, weekly plan, close).
- `PAGE.md`: each section's job, calculator logic, phone, WhatsApp, policy and film links.
- `assets/logo/`: full logo lockup, wordmark, leaf "A" mark.
- `assets/pack/`: high-res 2 kg pack cut-out, pack, sack, the pack's village scene.
- `assets/veer/`: Veer's supplied drawings (stand, wave, point, roti, think, thumbs, packet, bust) and a high-res standing cut-out.
- `assets/people/`: Dr. Asha Kawatra's photo.
- `assets/illustrations/`: the brand's own AI-made illustrations (stone chakki, chokar kept in, Sharbati wheat sack, Day 1 milled / Day 2 delivered pack, natural millstone, atta with rotis). Illustrations, never real photos.
- `inspiration/`: the owner's seven pictures, numbered by style. `STYLES.md` explains the six styles. These are the only styles a design may draw from.
- `archive/`: the retired design gallery, served at /archive/. Its `index.html` is the old root gallery with a banner pointing to the latest designs.
- `archive/opening/`: the earlier homepage directions (no longer in use), linked from the archive gallery. Old `/opening/...` links redirect here through `404.html`.
- `archive/opening/` (detail): eight homepage directions, linked from both galleries in display order.
  - Earlier directions: `8-morning-market/`, `9-glass-field/`, `10-golden-glass/` and `11-fresh-bento/`.
  - Shelved: `2-the-pack-speaks/` (available by direct link).
  - Latest references: `13-saffron-market/`, `14-golden-kitchen/`, `15-harvest-grove/` and `16-pure-and-simple/`. Each has its own static page and uses `reference-media/` for shared styles, navigation and imagery.
  - `shared/`: web-sized copies of the logo (full colour, white, black), pack, Veer drawings and brand illustrations that every direction uses.
  - `_gen/`: the raw Codex-generated concept images (full size) and the Veer reference copies used to make them.
  - `screenshots/`: phone (390 px) and desktop (1280 px) screenshots of each direction.
- `index.html`: the root page (GitHub Pages home). Says the designs have moved and links to the five Glass Field blends on the atulyash-website-redesign site, plus the archive.
- `404.html`: sends old `/opening/...` links to `/archive/opening/...`.
- `opening/CREDITS.md`: credits and licences for the real stock photos used (Pexels, Unsplash). Everything else is AI-made (not labelled on the page).
- `opening/_stock/`: full-size stock photos Codex downloaded, with `TASK.md` (its brief) and `CREDITS.md` for all 16. Not pushed; pages use resized copies in each `img/`.
- `.claude/launch.json`: serves `archive/opening/` locally on port 8765.
- Git: pushed to GitHub as `icemanbuilds/atulyash-fresh` (public, GitHub Pages from `main`). `archive/opening/_gen/`, `archive/opening/_stock/`, `archive/opening/screenshots/review/` and `.claude/` are left out by `.gitignore`.
