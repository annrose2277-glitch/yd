# Design Document: Yagna Dhruva '26 Contact Page

## Vision
A high-fidelity, single-file contact/helpdesk page for Yagna Dhruva '26. The design will be mobile-first, using a royal maroon and gold theme, custom inline SVGs for branding, and smooth CSS/JS animations.

## Specifications
- **Format**: Single `index.html` (HTML/CSS/JS).
- **Aesthetic**: Royal, regal, Indian-inspired.
- **Colors**: Deep maroon void (#150404) to gold accents (#dbb69c, #c9964f).
- **Typography**: Cinzel (Headers), Poppins (Body).
- **Graphics**: Hand-coded inline SVGs for the emblem and background textures.
- **Components**: Hero, Quick-Action Bar, Contact Cards (grouped), FAQ Accordion, Footer.
- **Accessibility**: WCAG AA, mobile-first, fluid typography.

## Strategy
1. **HTML Structure**: Semantic tags (header, main, section, footer).
2. **CSS System**: Root custom properties, fluid typography with `clamp()`, Flexbox/Grid for layout.
3. **SVG Implementation**: Complex paths for the circular seal and mandala patterns.
4. **JS Logic**: Intersection Observer for animations, simple accordion state management.
5. **Assets**: All fonts via Google Fonts, no external images.
