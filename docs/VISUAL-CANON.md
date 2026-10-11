# ZYXEL-LYN — Visual Canon V2 (Frozen)

Authoritative reference: the user-approved monochrome Arthur Boyle Pixel / manga GitHub layout.

## Immutable composition
- One full-width ZYXEL-LYN hero, including sword, character, hair above border, typography and right-side manga panel.
- Three Selected Work cards side-by-side, in this order: TA-Builder / DevNoteHub / web-personal.
- One horizontal footer: ABOUT / GET IN TOUCH / manga quote.
- Black, white and grayscale only. No gradients, neon, 3D, automated badges, or redesign of pixel details.
- Keep the authored pixel-art exactly as generated: no enhancement, smoothing, sharpening, retouching or recoloring.

## Approved asset policy — 2026-10-11
The final images originate from five **independent, full-frame generated PNGs** supplied by the user in
`D:\Wildanun Mukhallid\Project\Github Theme\New folder`.
They are not screenshot crops from the earlier GitHub UI mockup.

The user explicitly approved removing excess space **outside each artwork frame** while preserving
Arthur's hair above the hero frame. We cropped outer transparent margins with fixed integer rectangles.
No image was rescaled. Every original visible pixel retained in the crop is identical in BGRA channels.
Pixel-comparison QA also checked that discarded pixels have alpha no greater than 1.

| GitHub repository image | Final local image | Pixel size |
|---|---|---|
| `assets/hero-monochrome-v2-master.png` | `hero-monochrome-v2.png` | 2156 x 650 |
| `assets/project-ta-builder-master.png` | `project-ta-builder.png` | 1911 x 565 |
| `assets/project-devnotehub-master.png` | `project-devnotehub.png` | 1979 x 619 |
| `assets/project-web-personal-master.png` | `project-web-personal.png` | 1967 x 575 |
| `assets/manga-quote-master.png` | `manga-footer-v2.png` | 1945 x 502 |

Local source of truth: `D:\Wildanun Mukhallid\Project\Github Theme\FINAL_ASSETS`.

## Forbidden changes
- Replacing the approved character with AI-generated reinterpretations or smoothing away pixel edges.
- Cropping within borders, removing sword, hair, text, or illustration details.
- Replacing horizontal cards with stacked V3 banners.
- Editing the GitHub avatar. The account photo is maintained manually by the user.

## GitHub platform limitations
README content may use HTML tables and relative PNG references. GitHub controls top navigation,
sidebar, account avatar, pinned repositories, and contribution graph.
Three columns may look very small on narrow/mobile screens; do not silently alter the approved
composition to solve platform constraints.

## Acceptance and provenance
1. Five final images are PNG with transparency outside the framed compositions.
2. Crops are derived from originals without resampling or changing retained nontransparent pixels.
3. SHA-256 checksums match the validated local final assets after GitHub upload.
4. README image references resolve, rendering is visually checked, and characters/borders are intact.
5. GitHub avatar remains unchanged.
