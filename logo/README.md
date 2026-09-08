# Chi C◆ Logo

The canonical Chi mark is a simple **C◆** construction:

- a solid square rotated 45° to form the diamond background;
- the selected `Geekomet Demo` C typography centered on top;
- a fixed 100 × 100 viewBox and consistent proportions.

## Canonical variants

- `chi-mark-wb.svg`: black diamond with white C.
- `chi-mark-bw.svg`: white diamond with black C.

These preserve the vector construction used by the existing Chi NAV `wb.svg` asset. The original NAV asset defines the 100 × 100 mark, a 70 × 70 rotated square, and centered C typography. Product repositories should use these canonical assets rather than redrawing the mark.

## Branded-color variants

The logo may use a site's assigned brand color, but **the geometry and typography must never change**.

Preferred mapping:

| Site | Brand color | Recommended mark |
| --- | --- | --- |
| `chi.qzz.io` | `#356AE6` | Brand color diamond + white C |
| `nav.chi.qzz.io` | `#1687E8` | Brand color diamond + white C |
| `merch.chi.qzz.io` | `#0FA3A3` | Brand color diamond + white C |

For light/dark surfaces, choose the variant that maintains sufficient contrast. Do not introduce gradients, shadows, outlines, rounded corners, alternate C typography, or site-specific geometry into the core mark.

When implementation needs a colored mark, recolor the existing SVG shapes instead of creating a new logo drawing.

## Usage boundary

`chi-brand` owns the canonical identity. Product repositories own implementation details such as favicon wiring, asset paths, responsive sizing, and theme integration.
