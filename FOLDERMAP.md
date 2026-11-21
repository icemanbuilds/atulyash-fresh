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
- `opening/`: the homepage opening (Hero, Manifesto, The Atulyash way) built in nine directions: six from the inspiration styles, plus 7 and 8 copied from two fresh-brand references the owner sent. `index.html` links them all.
  - `1-rasoi-collage/` (fresh photo collage), `2-the-pack-speaks/` (product first), `3-stone-dark/` (dark immersive), `4-kitchen-almanac/` (botanical heritage), `5-veers-village/` (grainy flat illustration), `6-golden-hour/` (wheat field photo), `7-green-board/` (EverFood brand board, freshness first), `8-morning-market/` (Natura Market shop page, freshness first), `9-glass-field/` (frosted green glass cards on a dark wheat wall, with a sprig, Veer and the pack breaking out). Each has a static `index.html` and an `img/` folder of its own AI concept images and restyled Veer art.
  - `shared/`: web-sized copies of the logo (full colour, white, black), pack, Veer drawings and brand illustrations that every direction uses.
  - `_gen/`: the raw Codex-generated concept images (full size) and the Veer reference copies used to make them.
  - `screenshots/`: phone (390 px) and desktop (1280 px) screenshots of each direction.
- `index.html`: the root page (GitHub Pages home) showing a desktop and phone preview of each direction with a link to open it.
- `opening/CREDITS.md`: credits and licences for the real stock photos used (Pexels, Unsplash). Everything else is AI-made (not labelled on the page).
- `opening/_stock/`: full-size stock photos Codex downloaded, with `TASK.md` (its brief) and `CREDITS.md` for all 16. Not pushed; pages use resized copies in each `img/`.
- `.claude/launch.json`: serves `opening/` locally on port 8765.
- Git: pushed to GitHub as `icemanbuilds/atulyash-fresh` (public, GitHub Pages from `main`). `opening/_gen/`, `opening/_stock/` and `.claude/` are left out by `.gitignore`.
