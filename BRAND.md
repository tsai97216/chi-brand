# Chi Brand

> Shared visual identity for the Chi web ecosystem.

## Brand Structure

The Chi ecosystem uses one shared **C◆** logo system across its websites. The logo geometry, typography, and proportions remain consistent; individual sites may use different brand colors to establish their own product identity while remaining part of the same family.

## Websites

| Website | Role | Temporary primary color |
| --- | --- | --- |
| `chi.qzz.io` | Main Chi site | `#356AE6` |
| `nav.chi.qzz.io` | Tools / navigation | `#1687E8` |
| `merch.chi.qzz.io` | Collection database | `#0FA3A3` |

These colors are currently **provisional** and may be refined after implementation and visual review.

## Logo Principle

- Use the same core **C◆** mark across the ecosystem.
- The mark consists of the selected C typography with a solid square rotated 45° (a diamond) behind it.
- Keep the logo geometry, proportions, and typography consistent between sites.
- Color may vary by site, but the underlying logo identity should remain unchanged.

## Design System Principle

Brand identity and product UI are separate layers:

- `chi-brand` defines the shared brand identity and visual foundations.
- Each product repository defines how the brand is applied to its own interface.
- Product repositories should prefer semantic design tokens instead of scattering raw color values throughout CSS.

Recommended semantic color roles include:

- `--brand`
- `--brand-hover`
- `--brand-active`
- `--brand-soft`
- `--brand-border`
- `--brand-text`

## Status

This document records the initial shared brand direction. It is intentionally lightweight until the logo assets, color palette, typography, and usage rules are fully finalized.
