# The Moon As We Saw It

An experimental, source-led digital exhibit about how people around the world have observed, represented, mapped, and photographed the Moon.

## Run

Open `index.html` in a browser, or publish the repository using **Settings → Pages → Deploy from a branch → main → / (root)**.

No build tools or dependencies required.

## Navigation

- Select orbital dots or move the chronology slider.
- Use left/right arrow keys or previous/next buttons.
- For entries tagged as surface depictions, turn on comparison and move the wipe slider.
- Click the institutional source link to investigate the record.

## Research methodology and caveats

The curated dataset lives in `data/timeline.js`. It distinguishes observations and symbolic/calendar representations from actual lunar-surface depictions. A chronological position assigned to an undated living tradition is *not* a historical origin date. The collection is selective and global in scope, not exhaustive.

**Critical:** The central Moon is a schematic SVG, and the comparison textures are generated illustrative placeholders, not historical images or NASA data. Do not describe them as scans, reconstructions, or scientifically registered imagery. The next research phase should retrieve and license-check individual primary-source images, record rights/credit/access dates, and only enable precise visual wipes for images that can be properly oriented and aligned. Several entries have research caveats stated directly in the exhibit.

Institutional links are leads for verification, not a substitute for object-level research or peer-reviewed scholarship. Community-authored resources should be prioritized for living Indigenous knowledge systems.

## Structure

- `index.html` — semantic single-page exhibit
- `style.css` — responsive dark visual system
- `script.js` — orbit, timeline and comparison controls
- `data/timeline.js` — research candidates and source links

## Credits

Concept, curation and editorial direction: project creator. AI assistance used for research discovery, drafting and code prototyping; all public historical claims and image rights should be independently checked before release.
