## 2026-09-12 - Inline SVG brand icons & responsive quick links grid

**Learning:** Quick links with hardcoded emoji text cause inconsistent visual sizing across devices and operating systems. Standardizing on inline SVG icons wrapped in `--brand-color` containers provides dark-mode parity and crisp rendering.
**Action:** Use CSS Grid with 4 columns (`grid-template-columns: repeat(4, 1fr)`) for quick links layout and style brand icon wrappers with fallback CSS variables.
