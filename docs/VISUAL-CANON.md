# ZYXEL-LYN — Visual Canon V2 (Frozen)

**Authoritative reference:** the user-approved Arthur Boyle Pixel / black-white manga GitHub mockup.

## Immutable visual identity

- Arthur Boyle manga/pixel aesthetic, strictly monochrome black, white and grayscale.
- Preserve the original blocky pixel details, halftone, typography, sword, expressions, scene, composition, and decorative framing.
- Do not redraw, smooth, enhance, change contrast, recolor or reinterpret any artwork.
- Hero: one complete, full-width standalone banner.
- Selected Work: one row containing three equally sized cards in this order: TA-Builder, DevNoteHub, web-personal.
- Footer: ABOUT / GET IN TOUCH / manga quote, side by side.
- Do not replace this layout with stacked V3-style hero/cards, sliders, animations, trophies, colored badges or AI-style gradients.

## Production asset provenance

All five production images are independently generated, full-frame artwork.
They are **not** crops extracted from a screenshot of the GitHub interface.
The bytes uploaded into GitHub must match the standalone production PNGs and the
original user-provided artwork. All pixel content must remain unchanged.

| File in assets/ | Local master path under Github Theme/01_PRODUCTION/ | Source dimensions |
|---|---|---|
| hero-monochrome-v2-master.png | hero-monochrome-v2-master.png | 2172 x 724 |
| project-ta-builder-master.png | project-ta-builder-master.png | 1983 x 793 |
| project-devnotehub-master.png | project-devnotehub-master.png | 1983 x 793 |
| project-web-personal-master.png | project-web-personal-master.png | 1983 x 793 |
| manga-quote-master.png | manga-quote-master.png | 1983 x 793 |

**Local master folder:** `D:\Wildanun Mukhallid\Project\Github Theme`

**QA evidence:** `02_QA/ASSET_QA_REPORT.json` in the local master folder.
Source-to-production equality was verified by full byte comparison,
SHA-256 digest and PNG chunk CRC checks. Production art must not be cropped
or resampled to fit GitHub: display full frames at width 100% instead.

## Profile photo is out of scope

The user uploads/maintains the GitHub profile photo manually.
Do not replace or edit the GitHub avatar and do not publish a new avatar.

## Platform constraints

The GitHub header, side navigation, account avatar, pinned repositories,
contribution graph, and browser responsive behavior are GitHub-owned UI.
README Markdown controls only the profile README content.

Rendering can scale an entire image, which does not remove pixels but makes
small typography less readable at narrow widths. Revisit card composition
only after the user explicitly approves a different layout.

## Acceptance gates

1. Every master image is a complete, independently generated composition.
2. All five GitHub image files are pixel/byte-identical to the validated masters.
3. No clipped titles, borders or character elements are introduced by processing.
4. All image paths in README exist and render in GitHub.
5. Desktop/mobile screenshot QA performed before declaring the entire UI accepted.
6. Do not edit the user-controlled avatar.
