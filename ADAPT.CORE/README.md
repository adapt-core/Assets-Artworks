# ADAPT.CORE production asset system

Canonical source: `svg/primary-horizontal-full-color.svg`.

The logo is reconstructed from the supplied `assss.webp` reference. The symbol uses one canonical `stripe-master` path instantiated four times at mathematically consistent offsets. The `ADAPT.CORE` wordmark is custom vector path geometry; it is not live text and does not depend on an installed font.

## Assets

- `primary-horizontal-*`: full horizontal lockup.
- `stacked-*`: symbol above wordmark.
- `symbol-outline-*`: four outlined stripes.
- `symbol-solid-*`: solid micro symbol for 24 px and below.
- `wordmark-*`: custom path wordmark only.
- `square-*`: symbol-first profile/avatar assets with safe area.
- `print-*`: one-color production-safe versions.

## Responsive behavior

Use the canonical outlined symbol at 128, 64, 48 and 32 px. Use the dedicated solid micro symbol at 24, 16, 12 and 8 px when outline negative space no longer survives. Do not use the horizontal lockup at icon sizes.

## Color and backgrounds

Full color uses `#00A0E9`, `#003DBF`, `#173A9A`, `#E60012`. White and black versions are single-color path variants for transparent light/dark surfaces. No gradients, raster fills, effects or shadows are used.

## Safe area and minimum sizes

For symbol-first assets, reserve clear space equal to one stripe outline width (18% of symbol height) on every side. Keep the horizontal lockup at or above 128 px wide where the wordmark remains comfortably legible; use the symbol below that threshold.

## Print / engraving

Use `print-black.svg` or `print-white.svg` for monochrome documents, vinyl, embroidery, engraving and watermarking. These retain the four-stripe structure with a single solid color.

## Filename convention

`{lockup-or-symbol}-{color}-{size-or-use}.{ext}`. SVG is canonical; PNGs are raster deliverables generated from the approved SVGs only.
