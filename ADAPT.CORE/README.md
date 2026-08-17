# ADAPT.CORE Brand Assets

Brand assets for ADAPT.CORE.

- **SVG** files are the source/vector assets.
- **PNG** files are exports for platforms that require raster images.

---

## Brand Assets

### Primary Logo

The primary logo consists of the four-stripe symbol and the `ADAPT.CORE` wordmark.

Use it when there is enough horizontal space.

### Symbol

The four-stripe mark can be used by itself when the full logo is unnecessary or does not fit.

---

## Which File Should I Use?

| Use case | File |
|---|---|
| Website / README / documentation | `svg/primary-horizontal-full-color.svg` |
| Dark background | `svg/primary-horizontal-white.svg` |
| Light background | `svg/primary-horizontal-black.svg` |
| Square or vertical layout | `svg/stacked-full-color.svg` |
| Symbol only | `svg/symbol-outline-full-color.svg` |
| Small symbol, 24 px and below | `svg/symbol-solid-micro-full-color.svg` |
| Discord / GitHub / profile image | `svg/square-profile-full-color.svg` |
| Wordmark only | `svg/wordmark-full-color.svg` |
| Print / engraving / vinyl / embroidery | `svg/print-black.svg` |

---

## Symbol Sizes

Use the outlined symbol for normal icon sizes and the solid micro symbol at very small sizes.

| Size | Asset |
|---:|---|
| 128 px | `symbol-outline` |
| 64 px | `symbol-outline` |
| 48 px | `symbol-outline` |
| 32 px | `symbol-outline` |
| 24 px | `symbol-solid-micro` |
| 16 px | `symbol-solid-micro` |
| 12 px | `symbol-solid-micro` |
| 8 px | `symbol-solid-micro` |

Do not simply scale the outlined symbol down to very small sizes.

---

## Primary Horizontal Logo

### SVG

```text
svg/
├── primary-horizontal-full-color.svg
├── primary-horizontal-white.svg
├── primary-horizontal-black.svg
└── primary-horizontal-single-color.svg
```

### PNG

```text
png/primary-horizontal/
├── primary-horizontal-full-color-1024.png
├── primary-horizontal-full-color-512.png
├── primary-horizontal-full-color-256.png
├── primary-horizontal-full-color-128.png
├── primary-horizontal-full-color-64.png
├── primary-horizontal-full-color-48.png
├── primary-horizontal-full-color-32.png
├── primary-horizontal-full-color-24.png
└── primary-horizontal-full-color-16.png
```

PNG dimensions refer to the logo's width. The height remains proportional.

---

## Stacked Logo

Use the stacked version when a horizontal logo does not fit.

```text
svg/
├── stacked-full-color.svg
├── stacked-white.svg
└── stacked-black.svg
```

Suitable for:

- Square layouts
- Posters
- Cards
- Mobile layouts
- Vertical layouts

---

## Symbol — Outlined

```text
svg/
├── symbol-outline-full-color.svg
├── symbol-outline-white.svg
└── symbol-outline-black.svg
```

PNG exports:

```text
png/symbol-outline/
├── symbol-outline-full-color-128.png
├── symbol-outline-full-color-64.png
├── symbol-outline-full-color-48.png
└── symbol-outline-full-color-32.png
```

---

## Symbol — Solid

```text
svg/
├── symbol-solid-full-color.svg
├── symbol-solid-white.svg
└── symbol-solid-black.svg
```

---

## Symbol — Solid Micro

Use this version at 24 px and below.

```text
svg/
├── symbol-solid-micro-full-color.svg
├── symbol-solid-micro-white.svg
└── symbol-solid-micro-black.svg
```

PNG exports:

```text
png/symbol-solid/
├── symbol-solid-micro-full-color-24.png
├── symbol-solid-micro-full-color-16.png
├── symbol-solid-micro-full-color-12.png
└── symbol-solid-micro-full-color-8.png
```

---

## Wordmark

The wordmark contains only the `ADAPT.CORE` lettering.

```text
svg/
├── wordmark-full-color.svg
├── wordmark-white.svg
└── wordmark-black.svg
```

---

## Square Profile

Use the square profile version for avatars and profile images.

### SVG

```text
svg/
├── square-profile-full-color.svg
├── square-profile-white.svg
└── square-profile-black.svg
```

### PNG

```text
png/profile/
├── square-profile-full-color-512.png
├── square-profile-full-color-256.png
├── square-profile-full-color-128.png
└── square-profile-full-color-64.png
```

Recommended:

| Use | File |
|---|---|
| Discord | `square-profile-full-color-512.png` |
| GitHub | `square-profile-full-color-512.png` |
| Social profiles | `square-profile-full-color-512.png` |
| App icon | `square-profile-full-color-512.png` |
| Smaller avatar | `256.png` or `128.png` |
| Very small avatar | `64.png` |

The square profile asset is intended for square and circular crops.

---

## Monochrome

### White

For dark backgrounds:

```text
svg/
├── primary-horizontal-white.svg
├── symbol-outline-white.svg
├── symbol-solid-white.svg
├── symbol-solid-micro-white.svg
├── stacked-white.svg
└── wordmark-white.svg
```

### Black

For light backgrounds and single-color use:

```text
svg/
├── primary-horizontal-black.svg
├── symbol-outline-black.svg
├── symbol-solid-black.svg
├── symbol-solid-micro-black.svg
├── stacked-black.svg
└── wordmark-black.svg
```

---

## Print and Physical Production

Use:

```text
svg/print-black.svg
```

For:

- Monochrome printing
- Engraving
- Laser marking
- Vinyl cutting
- Embroidery
- Other single-color production

---

## SVG vs PNG

### Use SVG when possible

SVG is the preferred format because it can be scaled without losing quality.

Use SVG for:

- Websites
- GitHub
- Documentation
- Presentations
- Design work
- Print production

### Use PNG when SVG is not supported

Use PNG for:

- Discord uploads
- Social platforms
- Software that requires raster images
- Other platforms that do not accept SVG

---

## PNG Naming

The number at the end of a PNG filename is its exported size.

Examples:

```text
primary-horizontal-full-color-1024.png
```

The logo is **1024 px wide**.

```text
symbol-outline-full-color-48.png
```

The symbol is **48 × 48 px**.

```text
symbol-solid-micro-full-color-16.png
```

The symbol is **16 × 16 px**.

---

## Complete File Map

### Primary Horizontal

```text
svg/
├── primary-horizontal-full-color.svg
├── primary-horizontal-white.svg
├── primary-horizontal-black.svg
└── primary-horizontal-single-color.svg

png/primary-horizontal/
├── primary-horizontal-full-color-1024.png
├── primary-horizontal-full-color-512.png
├── primary-horizontal-full-color-256.png
├── primary-horizontal-full-color-128.png
├── primary-horizontal-full-color-64.png
├── primary-horizontal-full-color-48.png
├── primary-horizontal-full-color-32.png
├── primary-horizontal-full-color-24.png
└── primary-horizontal-full-color-16.png
```

### Stacked

```text
svg/
├── stacked-full-color.svg
├── stacked-white.svg
└── stacked-black.svg
```

### Symbol — Outlined

```text
svg/
├── symbol-outline-full-color.svg
├── symbol-outline-white.svg
└── symbol-outline-black.svg

png/symbol-outline/
├── symbol-outline-full-color-128.png
├── symbol-outline-full-color-64.png
├── symbol-outline-full-color-48.png
└── symbol-outline-full-color-32.png
```

### Symbol — Solid

```text
svg/
├── symbol-solid-full-color.svg
├── symbol-solid-white.svg
└── symbol-solid-black.svg
```

### Symbol — Solid Micro

```text
svg/
├── symbol-solid-micro-full-color.svg
├── symbol-solid-micro-white.svg
└── symbol-solid-micro-black.svg

png/symbol-solid/
├── symbol-solid-micro-full-color-24.png
├── symbol-solid-micro-full-color-16.png
├── symbol-solid-micro-full-color-12.png
└── symbol-solid-micro-full-color-8.png
```

### Wordmark

```text
svg/
├── wordmark-full-color.svg
├── wordmark-white.svg
└── wordmark-black.svg
```

### Square Profile

```text
svg/
├── square-profile-full-color.svg
├── square-profile-white.svg
└── square-profile-black.svg

png/profile/
├── square-profile-full-color-512.png
├── square-profile-full-color-256.png
├── square-profile-full-color-128.png
└── square-profile-full-color-64.png
```

### Print

```text
svg/print-black.svg
```

---

## Directory Structure

```text
ADAPT.CORE/
├── svg/
├── png/
│   ├── primary-horizontal/
│   ├── profile/
│   ├── symbol-outline/
│   └── symbol-solid/
├── preview/
├── source/
└── README.md
```

---

## Quick Reference

- **Full logo:** `primary-horizontal`
- **Symbol:** `symbol-outline`
- **32 px and above:** `symbol-outline`
- **24 px and below:** `symbol-solid-micro`
- **Profile / avatar:** `square-profile`
- **Single-color production:** `print-black`
- **Use SVG whenever possible**
- **Use PNG when the platform requires it**

---
