# ZYXEL-LYN / GitHub Profile Visual Lock

Version: V3 responsive implementation of the user-approved V2 visual canon (2026-10-11).

## Immutable visual direction

- Arthur Boyle pixel-art with high-contrast black/white manga panel vocabulary.
- Monochrome only: black, white, and neutral grays. No neon, gradients, 3D, glassmorphism, gimmick stats, contribution snakes, badges, or typing animation.
- Character art is re-composed from the V2-approved banner, not reinterpreted as new character artwork.
- The V2 hero asset is retained at `docs/approved-hero-v2.png` for visual regression and rollback history.

## Implemented layout

- A single full-width hero banner; supporting headline remains HTML text underneath for mobile legibility.
- Three **full-width stacked** project panels, each with a real working GitHub repository link and descriptive HTML/Markdown text outside the image for wrapping.
- About and Contact are native Markdown; no three-column HTML tables.
- No embedded screenshots or made-up project metrics. Project panels are editorial artwork, not application UI previews.

## Asset sizing and readability

- Hero: 1200 × 410 px.
- Project panels: 1200 × 160 px each.
- Intended image display width: 300–800 CSS px; responsive `width="100%"`.
- Artwork panels contain only short display text. Paragraph descriptions must remain native, selectable text.
- Avoid fixed-width tables, pixel sizes in Markdown that cause horizontal scrolling, or GitHub-incompatible CSS/JS.

## Acceptance and responsibilities

1. All 4 local README image paths must resolve to exact tracked blobs on the current default branch.
2. No horizontally overflowing HTML layout at narrow widths. Images shrink and text wraps naturally.
3. No duplication of project titles/descriptions below graphics.
4. GitHub owns the global navigation, avatar, About sidebar, pinned repos, and contribution graph. README cannot skin these areas.
5. GitHub avatar and pinned selection are **account-level manual changes** unless the connected GitHub app exposes a supported update action.

## Verification status

- Local pixel layout reviewed at 560 px and 360 px: PASS for alignment and legibility of primary titles.
- Browser DOM verification on the live GitHub site: must be checked after publishing; source/API validation is not a substitute.
- Original V2 README preserved in Git history, rollback using parent commit.
